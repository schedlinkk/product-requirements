# product-requirements
### Product Requirements Document (PRD)

#### 1. **Introduction**
- **Product Name**: Social Planner
- **Author(s)**: Andrii Sozonik
- **Last Updated**: 01/14/2025
- **Status**: Draft
- **Version**: N/A

#### 2. **Objective**
- **Purpose**: Create a social media application that functions as a personal planner, enabling users to manage their schedules effectively. The app will also allow users to share their schedules with friends and create shared schedules.
- **Goals**: Provide a user-friendly platform for personal and shared scheduling, fostering better time management and social connectivity.

#### 3. **Background**
- Many people struggle with managing their schedules and coordinating plans with friends or colleagues. Existing personal planner apps lack robust social features, while social media platforms do not focus on scheduling. This app aims to bridge that gap.

#### 4. **Scope**
- **In-Scope**:
  - Personal scheduling features.
  - Sharing schedules with friends.
  - Creating and managing shared schedules collaboratively.
  - Notifications and reminders.
  - Privacy controls for shared schedules.
- **Out-of-Scope**:
  - Advanced project management tools.
  - Integration with enterprise software.

#### 5. **User Personas**
- **Persona 1**: Alex, a busy college student who needs a personal planner but also wants to coordinate study group schedules.
- **Persona 2**: Jordan, a working professional who manages both personal and work-related plans and wants to share weekend plans with friends.
- **Persona 3**: Taylor, a parent organizing family activities and coordinating with other parents.

#### 6. **Use Cases**
- Alex creates a personal study schedule and shares it with their study group to collaborate on exam preparation.
- Jordan plans a weekend trip and shares it with friends, allowing them to suggest edits.
- Taylor sets up a shared schedule for family activities and invites their partner to contribute.

#### 7. **Requirements**
##### Functional Requirements
- Users should be able to create, edit, and delete personal schedules.
- Users can share their schedules with friends.
- Users can create shared schedules where multiple participants can add or edit events.
- Notifications for upcoming events or changes in shared schedules.
- Privacy settings for controlling who can view or edit shared schedules.

##### Non-Functional Requirements
- The system should handle up to 10,000 concurrent users.
- Data should sync in real-time across devices.
- Ensure data security and user privacy.

#### 8. **Wireframes and Design**
- Initial sketches to include:
  - A dashboard displaying personal and shared schedules.
  - A calendar view with color-coded events.
  - A "Create Schedule" screen with options for sharing.
- Design should emphasize usability and minimalism.

#### 9. **Technical Specifications**
- **Frontend**: React Native for cross-platform support.
- **Backend**: Node.js with Express.
- **Database**: MongoDB for storing user data and schedules.
- **Authentication**: OAuth 2.0 for secure login.
- **Notifications**: Firebase Cloud Messaging.


#### 10. **Timeline and Milestones**
- **Milestone 1**: Develop server and REST API. (2 weeks).
- **Milestone 2**: Develop frontend that interacts with backend server (2 weeks).
- **Milestone 3**: Testing and bug fixes (2 weeks).
- **Milestone 4**: Launch MVP (1 week).

#### 11. **Risks and Assumptions**
- **Risks**:
  - Difficulty in real-time data synchronization.
  - Potential privacy concerns with shared schedules.
- **Assumptions**:
  - Users will have access to the internet for real-time updates.
  - Users will be willing to share schedules with friends.

#### 12. **Appendix**
- Relevant links to research on scheduling apps.
- List of potential competitors and their feature analysis.

---
