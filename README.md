# Body Guard Booking System

## Overview
A platform for booking bodyguard and security services with user, guard, and admin functionalities

## Tasks
### PUR-1: Dashboard
#### Description
Develop a dashboard for admins to display critical metrics and KPIs related to users, venues, and overall platform performance.

#### Acceptance Criteria
- Dashboard is accessible to admins
- Metrics are displayed accurately

#### Subtasks
##### PUR-2: User Metrics Implementation
###### Description
Implement user metrics on the dashboard.

###### Acceptance Criteria
- Total registered users are displayed
- Active vs. inactive users are displayed
- Membership conversion rate is displayed
- User growth rate is displayed (trending indicator)

##### PUR-3: Venue Metrics Implementation
###### Description
Implement venue metrics on the dashboard.

###### Acceptance Criteria
- Total signed venues are displayed (and their status)
- New venues onboarded are displayed (over a given period)
- Guestlist engagement is displayed (how many users have guestlisted at each venue)
- Spending/Consumption is displayed (total aggregated spending per venue)
- Venue performance is displayed (weekly/monthly trends)

##### PUR-4: Events Metrics Implementation (if needed on the dashboard)
###### Description
Implement events metrics on the dashboard.

###### Acceptance Criteria
- Upcoming events count is displayed
- Most popular events are displayed (by guestlist sign-ups)
- Discount usage rate is displayed

### PUR-5: Venues Management
#### Description


#### Acceptance Criteria
- None provided.

#### Subtasks
##### PUR-6: Referrals Metrics Implementation
###### Description
Develop a module to manage venues.

###### Acceptance Criteria
- Number of referrals sent is displayed
- Referral conversion rate is displayed (referrals who become active users)
- Venue profiles can be managed
- Venue performance can be tracked

##### PUR-7: Venue Profile Management (Restaurant)
###### Description
Implement venue profile management for restaurants.

###### Acceptance Criteria
- Basic details are captured (Name, phone number, logo, type of venue, etc.)
- Contact information is captured (venue manager’s contact details)
- Business agreement details are captured (commission structure, discount rates, etc.)

##### PUR-8: Venue Status Management
###### Description
Implement venue status management.

###### Acceptance Criteria
- Signed/Not Signed status is displayed (active partnership with contractual agreement)
- Pending status is displayed (venue is in the process of being signed)
- Not Signed status is displayed (venue in early stage discussion or leads to follow up)

##### PUR-9: Venue Profile Management (Table Link)
###### Description
Implement venue profile management (table link).

###### Acceptance Criteria
- Name of the restaurant is captured
- Logo is uploaded
- Type of venue is selected (beach, restaurant, lounge, etc.)
- Commission details are captured (Pays Commission, percentage of commission, special rules on commission)
- Cuisine is captured
- Indoors/Outdoors seating is captured
- Bar details are captured
- Special events are captured
- Service time, opening time, and closing time are captured
- Price range is captured
- Discount details are captured
- Description/Caption is captured

### PUR-10: Venue Profiles (Clubbing)
#### Description


#### Acceptance Criteria
- None provided.

#### Subtasks
##### PUR-11: Venue Performance Metrics
###### Description
Implement venue profiles for clubbing.

###### Acceptance Criteria
- Total bookings and deep dive in every booking (name of person, email, restaurant within venue, time of booking, confirmation time, money spent)
- Average spend is calculated
- Integration with Google docs is enabled (for settlements)
- Red flags/issues are tracked (user complaints, refunds, etc.)
- Venue profiles can be created and managed

##### PUR-12: Venue Profile Management (Clubbing)
###### Description
Implement venue profile management for clubbing.

###### Acceptance Criteria
- Basic details are captured (Name, phone number, logo, type of venue, etc.)
- Contact information is captured (venue manager’s contact details)
- Business agreement details are captured (commission structure, discount rates, etc.)

##### PUR-13: Venue Status Management (Clubbing)
###### Description
Implement venue status management for clubbing.

###### Acceptance Criteria
- Signed/Not Signed status is displayed (active partnership with contractual agreement)
- Pending status is displayed (venue is in the process of being signed)
- Not Signed status is displayed (venue in early stage discussion or leads to follow up)

### PUR-14: Event Performance Tracking
#### Description


#### Acceptance Criteria
- None provided.
### PUR-15: Automated Notifications/Integration with WhatsApp
#### Description


#### Acceptance Criteria
- None provided.
### PUR-16: Users Management
#### Description


#### Acceptance Criteria
- None provided.

#### Subtasks
##### PUR-17: Venue Profile Management (Clubbing)
###### Description
Implement users management.

###### Acceptance Criteria
- Name of the club is captured
- Logo is uploaded
- Type of venue is selected (beach club, nightclub, lounge, etc.)
- Commission details are captured (Pays Commission, percentage of commission, special rules on commission)
- Guestlist details are captured
- Indoors/Outdoors seating is captured
- Bar details are captured
- Special events are captured
- Service time, opening time, and closing time are captured
- Max party size is captured
- Discount details are captured
- Event details are captured (Name, date and time, venue, event description, guestlist info, table bookings, discount details)
- Number of guestlist sign-ups are displayed
- Check-ins/attendance is displayed
- Discount usage is displayed
- Revenue generated is displayed (if data is available)
- Guestlist notifications are sent (confirmation, rejection, successfully deleted)
- Booking confirmation notifications are sent (status)
- Reminder notifications are sent (for upcoming events)
- Capacity/sell-out alerts are sent (inform admins or venue managers when an event is near capacity)
- User profiles can be managed
- User status is updated
- Referrals are tracked

##### PUR-18: User Profile Management
###### Description
Implement user profile management.

###### Acceptance Criteria
- Personal details are captured (Name, email, phone number, etc.)
- Status is updated (invited, active member, waitlist)
- Referral information is captured (who referred the user, how many people they have referred)

##### PUR-19: User Status Lifecycle
###### Description
Implement user status lifecycle.

###### Acceptance Criteria
- Invited status is updated (invitation sent, awaiting registration)
- Active member status is updated (approved membership, can use all services)
- Suspended/inactive status is updated (temporary or permanent restriction based on rules)

### PUR-20: Reporting & Analytics
#### Description


#### Acceptance Criteria
- None provided.

#### Subtasks
##### PUR-21: User History)
###### Description
Implement reporting and analytics.

###### Acceptance Criteria
- Events attended are tracked
- Venues visited are tracked
- Total spend is calculated (if integrated with financial data)
- Referrals made (and how many converted) are tracked
- User analytics are displayed
- Venue and event analytics are displayed
- Referral and marketing analytics are displayed

##### PUR-22: User Analytics
###### Description
Implement user analytics.

###### Acceptance Criteria
- Demographics are displayed (where applicable)
- Retention/churn rates are calculated
- Engagement metrics are calculated (average number of events attended per month)

##### PUR-23: Venue & Event Analytics
###### Description
Implement venue and event analytics.

###### Acceptance Criteria
- Revenue reports are displayed (per venue/event, if integrated with financial data)
- Attendance patterns are displayed (peak months, popular types of events)
- Conversion metrics are displayed (how many guestlist sign-ups actually attended)

### PUR-24: Roles & Permissions
#### Description


#### Acceptance Criteria
- None provided.
### PUR-25: KPIs to Track for Growth
#### Description


#### Acceptance Criteria
- None provided.

#### Subtasks
##### PUR-26: Referral & Marketing Analytics
###### Description
Implement tracking for the listed KPIs.

###### Acceptance Criteria
- Most successful referral channels are displayed
- Campaign performance is displayed (if running specific marketing campaigns)
- Admin role has full access to all modules and features
- Venue manager role has limited access to their own venue’s profile, events, and stats
- Support staff role has limited or read-only access to user profiles for support queries
- Weekly/Monthly Active Users (WAU/MAU) is displayed
- Member Conversion Rate is displayed
- Venue Satisfaction Score is displayed
- Event Fill Rate is displayed
- Average Spend per User is displayed
- Referral Rate is displayed
- Churn Rate is displayed

