Building software in large enterprise (big company) presents unique challenges. There is no magic cure. But some tips below might help

## Meetings
* In a big company, it tends to have too many meetings. Beware, too many meeting could kill productivity.
* Meeting without notes is unproductive (just a waste of time). Send minutes meeting right away after the call (while the food is still hot), and highlight action items and its owners (in bold or background color).
* Have at least once a week team call to discuss common topics. In this call, we close communication gaps.

## Scrums
* Daily scrum is an important call. But don't get carried away, make it short ~ maximum 30 minutes. 
* Discuss blocker in a meeting within the same day or at the latest the day after. If you prefer email than meeting, setup placeholder call (the day after) to discuss it if the problem yet to resolved
* Retrospective call is a good opportunity to get feedback from the ground. Do not skip it.
* Consider using the Slack channel (one channel per team) to replace daily scrum if team members are in the different timezone. It means 5 meetings less in a week. Good deal, huh? But ensure team members post 3 scrum notes (yesterday accomplishment - today task - any blocker?) in Slack at the beginning of working day.

## Timezone
* Timezone could be a challenge to work together. But make timezone as an advantage by establishing "follow the sun" development ~ 24 hours cycle development

## Working With Business
* Business commitment is paramount. Good business counterpart makes project easy, but the lazy ones are like bugs to the project. Escalate early if the business team does not commit to the project.
* You may consider asking for requirement sign-off or this sign-off or that sign-off, but be careful as this sounds like "Sign here. Anything outside this document is your mistake". Instead of requesting sign-off, make business understand that they need to be diligent in writing user story and ensure its completeness. If no user story is written, nothing will happen - even if it is discussed a thousand times. 
* Lazy business team will highlight issues in last minute or even during move to production. Make them understand at the early time that IT could not perform magic in last minute. Have them to test early.

## Working with Other Team
* Human is often selfish, and do not care the need for another team. Higher management role is important to ensure employees are working for as one big team, and share their vision.
* Consider rotate the team, and make employee aware about what happens on the other group
* Have team building session once a while will help.

## Testing
* Do not give a too long period of testing. Shorten it up to a week, and it will become more productive. IT should do due diligence before testing with business, to avoid getting burnt out.

## Developers
* Hire developers based on skillset. Prove the skillset use HackerRank
* If you outsource the work, you may get mixed skillset - senior and junior. Normally junior members will not help much; unless proven otherwise using HackerRank
* You would need some good amount of in-house resources and nurture the team. Fully relying on the vendor will not work, because the vendor will give different resources for each project, and new people will not care about the existing trash before them.

## Project Management
* Divide your team into few small teams, up to 5-6 members. Have one leader in the team that you could count on. Having team members bigger than 6 people is not productive

## Emails
* Too many emails would become unmanageable. You would lose track the important ones. Consider using "Slack" for the unofficial chat, and use "Github Issue" for potentially lengthy discussion.

## Code Management
* Move to Git in Github.com for version control; SVN is good, but it is over!
* Use pull request (PR). Only trust your lieutenants to merge and make them accountable for bad quality codes went to the system
* Use SonarCube to do automated code review upon pull request. Ask developers to fix SonarCube warnings before merge happen

## Tools
* Pamper developer with best terminals to work with. Happy developers are productive resources.
* Prefer Linux or Mac terminal for productivity and forced-learning. Likely your production system uses UX based system anyway. Thus, it is important that developers are familiar with it even during development.
* Track stories/issue in Github issue. Label it properly. Too many tools will just create confusion. 
* In a big company, you would receive a reservation from the old timer that used to work with the old tool. They just need an eye-opening moment.

## New things
* `Docker` is getting common these days and very useful too. Big companies are often slow in adopting it. But yours shouldn't. It would help to simplify devops.
* Move to cloud. But don't stop at moving your infrastructure apple to apple from the legacy data center to cloud, what's the benefit then? Almost none. Instead of that setup common `Kubernetes` cluster that could be used across the applications. 
* Consider use "serverless" / "cloud function" for small used cases.
* `GraphAPI`. This is the new generation of real-time integration. Its benefit is more obvious in a big company.

