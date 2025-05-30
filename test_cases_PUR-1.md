# Test Cases for PUR-1: Dashboard

## Task Description
Develop a dashboard for admins to display critical metrics and KPIs related to users, venues, and overall platform performance.

### Test Case TC_PUR-1_01
**Objective**: Verify dashboard functionality.
**Preconditions**: System is accessible, user is logged in (if applicable).
**Test Steps**:
1. Ensure dashboard is accessible to admins.
2. Ensure metrics are displayed accurately.
**Expected Result**:
- Dashboard is accessible to admins
- Metrics are displayed accurately

## Subtask Test Cases
### Test Case TC_PUR-2_01
**Objective**: Verify user metrics implementation functionality.
**Preconditions**: Parent task functionality is available, user is logged in (if applicable).
**Test Steps**:
1. Ensure total registered users are displayed.
2. Ensure active vs. inactive users are displayed.
3. Ensure membership conversion rate is displayed.
4. Ensure user growth rate is displayed (trending indicator).
**Expected Result**:
- Total registered users are displayed
- Active vs. inactive users are displayed
- Membership conversion rate is displayed
- User growth rate is displayed (trending indicator)

### Test Case TC_PUR-3_01
**Objective**: Verify venue metrics implementation functionality.
**Preconditions**: Parent task functionality is available, user is logged in (if applicable).
**Test Steps**:
1. Ensure total signed venues are displayed (and their status).
2. Ensure new venues onboarded are displayed (over a given period).
3. Ensure guestlist engagement is displayed (how many users have guestlisted at each venue).
4. Ensure spending/consumption is displayed (total aggregated spending per venue).
5. Ensure venue performance is displayed (weekly/monthly trends).
**Expected Result**:
- Total signed venues are displayed (and their status)
- New venues onboarded are displayed (over a given period)
- Guestlist engagement is displayed (how many users have guestlisted at each venue)
- Spending/Consumption is displayed (total aggregated spending per venue)
- Venue performance is displayed (weekly/monthly trends)

### Test Case TC_PUR-4_01
**Objective**: Verify events metrics implementation (if needed on the dashboard) functionality.
**Preconditions**: Parent task functionality is available, user is logged in (if applicable).
**Test Steps**:
1. Ensure upcoming events count is displayed.
2. Ensure most popular events are displayed (by guestlist sign-ups).
3. Ensure discount usage rate is displayed.
**Expected Result**:
- Upcoming events count is displayed
- Most popular events are displayed (by guestlist sign-ups)
- Discount usage rate is displayed

