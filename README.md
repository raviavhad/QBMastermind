# QBMastermind

**Inspiration**

Presenting our solution for E Y GDS Hackpions  **Q B Mastermind** . With key focus on this Appathon on modernizing productivity bottlenecks and business inefficiencies that are holding back the team, we are presenting a solution which can solve the **problem faced by application operations teams from more than 2 years**.   


**Solution Background**

Reporting is a **very important task** for any team and more important for the operations team to give the insights of IT Applications health to business stakeholders.  For multiple application in production there are many best in class tools available to assist different processes, but, the restriction for custom reporting automation is affecting teams productivity in reporting.  **12 to 15 percent of team's bandwidth is used for manually preparing excel based reports by extracting data from ITSM tools, and then manually adding the data and logic in excel reports**.   Similar set of tasks are done by more than 5 teams for their respective tracks.  In the past there were **multiple initiatives to automate portions of this manual reporting process but No End To End Automation achieved yet**.  Multiple pain points including recurring mundane tasks, error in manual report, high bandwidth utilization, data duplication, manual emails and no option for data validation for the stake holders.

**Solution Features** - 

1. **100% ROI in less than 1 Week**: Solution built in less than 24 hours and the effort the solution save will ensure that the return of investment is less than a week.

2. **KPI Based Reports**: The KPI Based reports will give meaningful insights to the business stakeholders regarding application health and team performance. 

3. **Automated Reports**: Realtime Integration with tools and automated report generation

4. **Significant Cost Savings**: 450 hours/year savings for 1 Team, *2000 hours/year savings for 5 Teams 

5. **End to End Automation**: Complete automation for the reporting workflows, no manual inputs needed.

6. **Real Time Analytics**: Application and team related insights available at real time.

7.  **Collaboration with Team**: Realtime collaboration with the team.

8. **Saving Team Bandwidth**: Saved bandwidth can be re-invested for more innovation and this could yield compounded benefits.


**How we built it**

The QB Mastermind solution comprises of multiple entities, namely 	Incidents, Activities, Service Level Agreement, Knowledge Base, Communication, Teams, Groups and more.  There are **multiple user personas** available in the solution 

We will first look the solution from **Managers perspective**. Here in the home page we see various reports and charts which will give him the **insights of incident management by the team, workload spread across teams, types of incident in the queue, team performance and team bandwidth utilization**. In addition to that, a summarized report of incident is available for review which has **informative indicator for Service level agreement mapping**, and effort spent by the teams on the incidents. The same home page also has a report, which draws attention towards the incidents which have age of more than 5 days. Many times an incident moves between multiple teams, and tracking the incident assignment and effort spent on the incident can be really challenging if done manually, our solution automates this process. The manager can click on the reports to see the drill down details of the report. For any queries on the incident, the manager can add new communication which will go the team working the incident.   On the left hand menu there is option of adding communication, search any individual incident.  

The Effort spent by the team on particular incident is calculated by **including only working hours and excluding after office hours and weekend**. This task was done manually earlier and was the **most tedious** of all the tasks. The SLA Indicator uses Quickbase formulas to **smartly calculate the SLA adherence** and takes into account the effort spent and the SLA based on the priority of the incident.

One more striking feature of the platform is, the way to track the effort spent by the team. The reports will give early insights to the manager to understand if the team is **underutilized or overloaded**, this will help him to mobilize the team members to reduce the burden on overloaded teams, and **efficiently utilize the underutilized team**	. For example, application development team can help our application operations team if they have bandwidth available and vice versa. 

The QB Mastermind solution efficiently uses the pipelines to automate the process collating data from state of art of ITSM tool using channel.
The pipelines is automatically triggered every time a new incident is added or existing incident is updated in the ITSM Tool.
Workflow automation including monitoring of the fields changed and taking action accordingly. 

From Team Member's perspective the solution acts as **single source of truth** for the reports. Reports and the dashboard will be generated automatically based on the data received. Additionally, there is Knowledge Repository will help team long run to create summarized version of knowledge insights for similar or frequently occurring similar incidents. 

**Challenges we ran into**

Integration challenges between low code platform and capabilities/APIs provides by the ITSM Platforms. This enforced us to think differently - developed additional layer of abstraction exposing course grained API end points that matches the workflow requirements.

In addition to that, there  were we challenges with the way data was received. **Incomplete metadata** received from the upstream system. We built our own **automated data transformation workflow** to standardize the data, 

**Accomplishments**

First and foremost we are solving a problem which has been hampering the team productivity of for than 2 years. To be able to do that in such a short duration is sometime which we are really proud of. Faster transformation will bring along change the mindset of the team to look at solving the problem at hand rather than spending tireless effort on the workaround. In a hyper-personalized world, making new solutions quickly that work the same across an omnichannel ecosystem is a game changer.

With this solution there are far fewer bugs and integration problems to deal with now that the parts are standard, pretested, and ready to use than there were in the past, because the parts are already made. By spending less time on maintenance, developers can work on new ideas that add more value to the business.

**What we learned**

People came up with ideas for how we could get to the right problem to solve. Design thinking was used to write down the problems that were most important to deal with after the pandemic.
How could we try out different tech stacks to get more speed and flexibility?


## What's next for QB Mastermind

There are so many thing completed in just 24 hours and as we progress there so many other ideas which to mind which can add more value to the solution.
24 hours of Innovation using Quickbase can save close to 450 hours for one team and more than 2000 hours for 5 or more teams. If these 500 or 2000 hours are used for more innovation then the possibilities are endless. 

Looking forward to add more features to QB Mastermind: 

	- Training the Machine learning model on the data and integrating QB mastermind with Machine Learning Models for Predictive Analysis
	- Custom Integrations: Planning to add more custom integrators to broaden the scope of data collection.
	- Reinvesting saved effort to fuel more innovation
