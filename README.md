# Interaction Design and Process Modelling Assignment

![TransportBookingPortalBanner](https://github.com/user-attachments/assets/d65dcde7-8128-445a-9922-40110fc6178e)
---

**Assignment**  
s227284240  
**Tinotenda Mhedziso**  
>[!NOTE]
>This transport booking portal User Interface is adapted from Nelson Mandela University. The project is a simple website that shall not be revised after the conclusion of the investigation.




---
## Introduction

Nelson Mandela University has approximately 32,000 students enrolled for the 2024 academic year. A large portion of these students utilize the university's shuttle services. This assignment analyzes the correlation between the use of the transport booking portal and the shuttle service system through surveys, storyboards, and a summary of findings.

To understand the system under investigation, accessible [here](https://example.com), this report evaluates the interface design based on Ben Shneiderman's **8 Golden Rules of Interface Design (1986):**

1. **Strive for Consistency**: Ensure a consistent aesthetic and functional pattern.
2. **Seek Universal Usability**: Design for all types of users, regardless of skill level or resources.
3. **Offer Informative Feedback**: Keep users informed of their actions’ outcomes.
4. **Design Dialogues to Yield Closure**: Use clear, chronological workflows.
5. **Prevent Errors**: Facilitate valid data entry and guide users in resolving errors.
6. **Permit Easy Reversal of Actions**: Allow users to undo actions flexibly.
7. **Keep Users in Control**: Ensure users have control over their interactions.
8. **Reduce Short-Term Memory Load**: Minimize the need to remember details when navigating.

## System Analysis

The **NMU Transport Booking Portal** is a website designed for students to book shuttle services. While primarily targeting off-campus students, on-campus users can also benefit. Below is the user process flow:

### Process Flow

1. **Login Page**: Users log in using their NMU student credentials (student number and PIN).
2. **Morning Trip Page**: Users select morning trip details:
   - Pick-up Location
   - Trip Allocation Times
   - Drop-off Location
3. **Afternoon Trip Page**: Similar to the morning trip page, but pick-up and drop-off options are reversed for logical consistency.
4. **Detail Confirmation Page**: Users review their selections.
5. **Confirmation**: Booking details are saved, and a confirmation email is sent to the user’s student email.

Users can navigate to their booking history or sign out using the profile menu.

### Storyboards

| **Laptop View** | **Mobile View** |
|------------------|------------------|
| 1. Login Page ![image](https://github.com/user-attachments/assets/9d519a24-a260-4387-b985-49ea2b7347fc) | 1. Login Page  ![image](https://github.com/user-attachments/assets/9af576c8-af08-421d-858c-a9b969b90f83)|
| 2. Morning Trip Page ![image](https://github.com/user-attachments/assets/4cee576f-c3cf-4911-8974-5386c4e3649c)| 2. Morning Trip Page ![image](https://github.com/user-attachments/assets/99c55513-cf7f-4938-8ab0-8e32c1d6da96) |
| 3. Afternoon Trip Page ![image](https://github.com/user-attachments/assets/36c66fb2-af0b-4633-b1ad-6272ca6299ce) | 3. Afternoon Trip Page ![image](https://github.com/user-attachments/assets/eea213be-ab1a-4982-aca3-71c7a94a4ee7)|
| 4. Detail Confirmation Page ![image](https://github.com/user-attachments/assets/594ab28a-6727-44a5-82f3-6f82f3bcbab4) | 4. Detail Confirmation Page ![image](https://github.com/user-attachments/assets/8f29e0a0-ffda-443d-81b9-9a5a40b962a3) |
| 5. Receive Confirmation Page  ![image](https://github.com/user-attachments/assets/304737e3-f848-4027-8965-48d76e8d8d19) | 5. Receive Confirmation Page ![image](https://github.com/user-attachments/assets/603f5489-14c9-4dbe-8d57-6f1a3f7a84bd)|

## User Data 

A snapshot of some user data collected from NMU students:
![image](https://github.com/user-attachments/assets/83a2e58e-795b-4a25-8356-a6d3d1aafd95)

![image](https://github.com/user-attachments/assets/0d1e7dfe-cdd7-4e6d-9463-46c9e28a13ef)

![image](https://github.com/user-attachments/assets/ccfdf7a7-a910-47cb-858f-b4c5527ab452)


## User Data Analysis

A survey conducted using [Microsoft Forms](https://forms.office.com/r/HmxVbVpJRN) collected responses from NMU students, including shuttle and non-shuttle users. Factors such as qualification, year of study, and residence were considered to ensure diverse representation.

### Data Summary

| **Category**               | **Insights**                   |
|----------------------------|--------------------------------|
| General User Experience    | Average                       |
| Accessibility              | Above Average                 |
| Graphical Design           | Below Average                 |
| System Usefulness          | Excellent                     |

Detailed survey results are accessible [here](https://forms.office.com/Pages/DesignPageV2.aspx?subpage=design&FormId=s-5wvTelWkOTfHzTMNx02KjrT43ccIhHnzePSdcPMtBURExITU05WjZKRDRNMEFMR081UlJJQTI3QS4u&Token=cf87fcca29d646959ec0b6664802053d).

### Identified Issues

1. **Graphical Design**:
   - Poor use of whitespace and alignment.
   - Combo-boxes misaligned with the grid.
   - Awkward button placements.
2. **Duplicate Elements**:
   - Multiple non-functional “Home” buttons.
   - Redundant profile icons.
3. **Terminology Confusion**:
   - Mislabeling PIN input field as "password."

### Proposed Improvements

- Realign combo-boxes to fit within the containing grid.
- Enhance whitespace utilization for better readability.
- Consolidate duplicate elements (e.g., Home buttons, profile icons).
- Rename the “Password” field to “PIN.”

## User Persona

| **Attribute**      | **Details**                    |
|---------------------|-------------------------------|
| Name               | Lincoln McKnight              |
| Age                | 21                            |
| Gender             | Male                          |
| Ethnicity          | African                       |
| Career Position    | Student                       |
| Qualification      | Bachelor of IT                |
| Residential Location | Central                      |
| Problem Statement  | Navigating the NMU transport portal is frustrating and time-consuming.

## Redesigned Transport Booking Portal

The proposed redesign focuses on enhancing the interface through improved alignment, better utilization of whitespace, and addressing redundancy in design elements. Additional features like booking for specific dates and locations will improve usability further.

## Conclusion

The NMU Transport Booking Portal demonstrates high usability in its current form, but significant improvements are needed in its graphical interface. By addressing alignment issues, improving terminology, and reducing redundancy, the portal can provide a more user-friendly and engaging experience.

---

[Survey Form](https://forms.office.com/r/HmxVbVpJRN) | [Survey Design Page](https://forms.office.com/Pages/DesignPageV2.aspx?subpage=design&FormId=s-5wvTelWkOTfHzTMNx02KjrT43ccIhHnzePSdcPMtBURExITU05WjZKRDRNMEFMR081UlJJQTI3QS4u&Token=cf87fcca29d646959ec0b6664802053d)

<p align="center" style="font-family: 'Times New Roman', serif;">
  <a href="https://dev.to/passionoverpain">Dev.to</a> |
  <a href="mailto:tinomhedziso21@gmail.com">Email</a> |
  <a href="https://github.com/Passion-Over-Pain">GitHub</a> |
  <a href="https://www.linkedin.com/in/tinotenda-mhedziso/">LinkedIn</a> |
  <a href="https://tinotenda-mhedziso.pages.dev/">Website</a>
</p>

