# Test Cases

## Project

Online Learning Platform

---

# TC-001

## Test Scenario

Verify personalized greeting displays logged-in learner name

### Preconditions

* Learner account exists
* Valid credentials available

### Steps

1. Open login page
2. Enter valid credentials
3. Click Login
4. Wait for dashboard to load
5. Locate greeting section

### Expected Result

Dashboard greeting displays the correct authenticated learner name.

---

# TC-002

## Test Scenario

Verify placement test CTA opens placement test

### Preconditions

* Learner is logged in
* Placement test is available

### Steps

1. Navigate to dashboard
2. Locate placement test section
3. Click placement test CTA

### Expected Result

User is redirected to the placement test page successfully.

---

# TC-003

## Test Scenario

Validate zero-value metrics rendering

### Preconditions

* Test account with zero progress metrics

### Steps

1. Log in with test account
2. Open dashboard
3. Locate statistics panel

### Expected Result

Metrics display value "0" correctly without layout issues or missing content.

---

# TC-004

## Test Scenario

Verify profile page recovery after endpoint restoration

### Preconditions

* Profile endpoint was previously unavailable
* Endpoint has been restored

### Steps

1. Refresh dashboard
2. Click "Mi Perfil"
3. Observe page load

### Expected Result

Profile page loads successfully and profile information is displayed.

---

# TC-005

## Test Scenario

Verify duplicate masterclass booking prevention

### Preconditions

* Learner already booked into a masterclass

### Steps

1. Open booked masterclass
2. Attempt to book again

### Expected Result

System prevents duplicate booking and displays appropriate feedback.
