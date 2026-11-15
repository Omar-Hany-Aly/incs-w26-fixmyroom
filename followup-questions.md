## 1. Budget & Timeline
* **Currency:** Can you confirm the currency for the **25K** one-off and **3K/year** operational budget?

  **Client's answer:** Euros. 25,000 EUR one-off and 3,000 EUR per year for operation.

* **Scope vs. Budget:** Does the 25K budget need to cover third-party software licensing, initial setup, and training, or is it strictly for custom development?

  **Client's answer:** Not decided yet, what would you suggest? The numbers I have are the two I gave you: 25,000 EUR one-off, 3,000 EUR per year for operation.

* **Timeline Constraint:** Is **October 27th** a hard launch date or a soft target for a beta/pilot release? What is driving this specific deadline?

  **Client's answer:** Let me correct that first: it is not 27 October. Go-live is before the winter semester 2027, so by Friday 1 October 2027; the date is set by the start of the winter semester. A beta or pilot before that: not decided yet, what would you suggest?


---

## 2. Technical & Offline Constraints
* **Offline Functionality:** Since the basement and plant room lack signal and hardware upgrades are out of budget, will staff need **offline sync capability** on their Android 11 devices to view and update work orders in dead zones?

  **Client's answer:** Yes. In the basements and plant rooms there is no signal, so caretakers must be able to see their assigned jobs and record their work offline, and everything synchronizes when they are back online.

* **Hardware/OS Compatibility:** Are there any security or technical policies preventing web apps or progressive web apps (PWAs) from running on the **Android 11** devices?

  **Client's answer:** That's your job. My caretakers have their phones and that's it: the existing company Android phones, Android 11, and there is no budget for new devices. Whether a policy blocks web apps on them, I don't know; I'd have to check with Ms. Vogel.

* **Notifications:** Given the 2-hour SLA for emergencies, how should caretakers receive urgent alerts if they are currently in a zero-signal area (e.g., fallback SMS, loud audio alarm, local caching)?

---

## 3. Workflow & Triage
* **On-Call Caretaker Assignment:** How is the "primary caretaker on call" selected or rotated? Is there an existing schedule/roster system that needs to be integrated?
* **"Response" Definition:** Since *“Response doesn’t mean it’s fixed, means it was seen,”* how should a caretaker acknowledge receipt of a request in the system? Should it automatically notify the resident that their issue has been reviewed?
* **Miscategorization:** Since miscategorization causes conflict, should the system guide residents through a decision tree or questionnaire to ensure requests are tagged correctly before submission?

---

## 4. Resident & Caretaker Communication
* **Communication Channels:** Are we looking to replace both the paper form and email process with a central portal/app, or should email integration remain as an input channel?
* **Tone & Language:** To address negative communication tone, should the system provide pre-written, standardized template responses for status updates?
* **Language Support:** Do residents or caretakers require multi-language support in the interface?

---

## 5. Reporting & Tracking
* **Daily 7:30 AM Shift List:** How is the housing office currently distributing the 7:30 AM caretaker list, and should the new system automate shift tracking?
* **Analytics:** Is tracking SLAs (e.g., verifying if emergencies were seen within 2 hours or urgent items solved in 24 hours) a required feature for management?