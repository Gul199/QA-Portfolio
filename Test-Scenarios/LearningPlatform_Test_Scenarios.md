# Test Scenarios

## Project

Online Learning Platform

---

## TS-001 Header & Profile Navigation

### Objective

Verify learner profile navigation functionality.

### Scenarios

* Verify personalized greeting displays logged-in learner name
* Verify greeting persists after dashboard refresh
* Verify long learner name renders correctly
* Verify profile navigation redirects successfully
* Verify profile page recovery after endpoint restoration

---

## TS-002 Statistics Panel

### Objective

Verify statistics cards display accurate learner progress information.

### Scenarios

* Verify all statistics cards display
* Verify displayed values match backend data
* Validate zero-value metrics rendering
* Validate rendering of large metric values
* Verify null or undefined metric handling
* Verify equal spacing and visual consistency
* Verify metric update after data refresh

---

## TS-003 Placement Test Section

### Objective

Verify placement test availability and navigation behavior.

### Scenarios

* Verify placement test card is visible
* Verify CTA opens placement test
* Verify progress state reflects actual progress
* Verify completed test state behavior
* Verify inaccessible test behavior
* Verify invalid route handling
* Verify CTA button visual consistency

---

## TS-004 Masterclass Booking

### Objective

Verify learner can browse and book available masterclasses.

### Scenarios

* Verify available masterclasses display correctly
* Verify booking confirmation behavior
* Verify duplicate booking prevention
* Verify full session handling
* Verify cancellation workflow
* Verify booking status persistence
* Verify responsive behavior on different screen sizes
