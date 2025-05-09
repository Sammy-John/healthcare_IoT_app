# Assumptions and Constraints

## Assumptions

- Users will have access to basic internet-connected smart devices (e.g., smartphone, TV).
- Caregivers or family members may assist during initial setup if needed.
- IoT sensors are pre-configured or provided in compatible formats for easy setup.
- Voice assistants (e.g., browser speech APIs) are functional on target devices.

## Constraints

- Limited to open-source tools and freely available APIs.
- Voice interaction is subject to browser/device capabilities.
- Accessibility goals aligned with WCAG 2.1 AA compliance at minimum.
- Local-first data processing; cloud syncing is excluded from MVP.
- No integration with government or clinical health data systems.

## Privacy and Ethical Considerations

Given the sensitive nature of health and behavioral monitoring, special care is taken to ensure:

- **User Consent:** All data collection is opt-in and designed to respect the autonomy of the patient.
- **Non-Invasive Monitoring:** Preference is given to ambient and behavioral sensors that avoid direct surveillance (e.g., no cameras or microphones unless explicitly permitted).
- **Data Minimization:** Only essential data is collected and stored, reducing exposure of personal hygiene habits.
- **Local Processing:** Health data is processed locally on the device (e.g., Raspberry Pi) where possible to minimize cloud exposure.
- **Transparent Data Use:** All stakeholders are informed of what data is collected, why, and how it is used.
- **User Dignity:** Features such as hygiene tracking or meal prep monitoring are designed to alert caregivers discreetly, avoiding embarrassment or perceived surveillance.
- **Ethical Focus:** No video/audio surveillance; monitoring is always consent-based and non-invasive.

Balancing **safety and dignity** is a core design principle of ConnectedCare.