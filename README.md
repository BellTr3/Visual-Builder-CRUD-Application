# Visual-Builder-CRUD-Application
A cloud-based CRUD application developed using Oracle Visual Builder Studio (VBS) with Oracle Autonomous Transaction Processing (ATP) Database integration for data management.
## Application Workflow

The HR Web Application follows a simple cloud-based architecture where the user interface communicates with the Oracle ATP database through REST-based services.

### Step-by-Step Flow

1. **User Interaction**

   * The user accesses the HR Web Application built using **Oracle Visual Builder Studio**.
   * The dashboard displays employee information such as **Name, Email, Job Role, and Salary**.

2. **UI Event Trigger**

   * When a user performs an action (Create, Update, Delete), the Visual Builder page triggers the corresponding event.

3. **REST Service Call**

   * Visual Builder sends a request through **REST Data Services** to interact with the backend database.

4. **Database Processing**

   * The request is processed by the **Oracle Autonomous Transaction Processing (ATP) Database**.

5. **Response to Application**

   * The database returns the updated data to the Visual Builder application.

6. **UI Update**

   * The application dynamically updates the **employee table and salary chart** to reflect the latest changes.

---

## Example CRUD Flow

**Create Employee**
User enters employee details → Visual Builder sends POST request → ATP database stores record → UI refreshes employee list.

**Update Employee**
User edits employee information → PUT request sent to database → record updated → table refreshed.

**Delete Employee**
User deletes an employee → DELETE request sent → record removed from ATP → dashboard updates automatically.

---

## Data Visualization

The dashboard includes a **salary distribution chart** that visually represents employee salary information.
This allows users to quickly analyze salary differences among employees.

---

## Project Purpose

This project demonstrates how developers can build **low-code cloud applications using Oracle Visual Builder Studio and integrate them with Oracle Autonomous Transaction Processing (ATP) Database** for enterprise data management.
