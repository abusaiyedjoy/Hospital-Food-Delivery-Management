# Hospital Management System

A comprehensive web-based application to manage hospital food services efficiently. The system includes three distinct user roles: **Hospital Food Manager**, **Inner Pantry Staff**, and **Delivery Personnel**, ensuring seamless management of patient diets, food preparation, and delivery.

---

## Key Features

### 1. Hospital Food Manager Functionality:
- **Manage Patient Details:**
  - Patient Name, Diseases, Allergies, Room Number, Bed Number, Floor Number, Age, Gender, Contact Information, Emergency Contact, etc.
- **Create Food/Diet Charts:**
  - Morning, Evening, and Night meal plans.
  - Specify ingredients and include specific instructions (e.g., "no salt," "low sugar").
- **Manage Inner Pantry:**
  - Input pantry details (Staff Name, Contact Info, Location).
  - Assign food preparation and delivery tasks to pantry staff.
- **Track Meal Preparation and Delivery:**
  - Monitor preparation status of each meal.
  - Track delivery statuses for Morning, Evening, and Night meals.

### 2. Inner Pantry Functionality:
- **Manage Food Preparation Tasks:**
  - View assigned tasks from the Hospital Food Manager.
  - Update preparation statuses.
- **Manage Delivery Personnel:**
  - Add delivery personnel details (Name, Contact Info, etc.).
  - Assign meal boxes to delivery personnel.
- **Track Meal Deliveries:**
  - Include details of each meal box (Patient Info, Room Number, Diet Chart Details).
  - Mark meals as "Delivered" with updates visible to all relevant parties.

### 3. Delivery Personnel Functionality:
- **Mark Deliveries as Completed:**
  - View assigned meal boxes with patient and delivery details.
  - Mark deliveries as "Done" with timestamps and optional notes.

### 4. Dashboards:
- **Hospital Food Manager Dashboard:**
  - Track all food deliveries and monitor delays or issues.
  - View patient details, diet charts, and pantry performance.
- **Inner Pantry Dashboard:**
  - Monitor meal preparation and delivery tasks.
  - Manage delivery personnel and assigned meal boxes.

---

## Technologies Used

### Backend:
-- Options: Node.js, Express.js

### Frontend:
- **Functionality:** React.js, Vite.js
- **Styling:** Tailwind CSS

---

## Requirements

### Backend:
1. **API Development:**
   - Implement authentication (JWT).
   - CRUD operations for patient details, diet charts, and delivery management.
   - Mark deliveries as complete.
2. **Database Structure:**
   - Patient Details
   - Diet Chart Details
   - Pantry Staff and Delivery Personnel Details
   - Delivery Details and Statuses

### Frontend:
1. **Dashboards for:**
   - Hospital Food Manager
   - Inner Pantry Staff
2. **Responsive and User-Friendly Forms:**
   - Add/Edit patient details.
   - Create and assign food/diet charts.

### Deployment:
- Deploy the application on a free platform (Vercel, Render).

---

## Setup Instructions

### Prerequisites:
- Node.js installed
- MongoDB database setup

### Installation:
1. Clone the repository:
   ```bash
   git clone https://github.com/abusaiyedjoy/hospital-management-system.git
   ```
2. Navigate to the project directory:
   ```bash
   cd hospital-management-system
   ```
3. Install dependencies for backend and frontend:
   ```bash
   npm install
   ```
4. Set up environment variables:
   - Create a `.env` file and configure database connection, JWT secrets, etc.
5. Start the development server:
   ```bash
   npm run dev
   ```

---

## Deployment

1. Deploy the backend to platforms like Render or vercel.
2. Deploy the frontend to platforms like Vercel or Netlify.
3. Update the environment variables for production.

---

## Testing Credentials

Use the following credentials to test the application:

| Role                 | Email                          | Password     |
|----------------------|--------------------------------|--------------|
| Hospital Manager     | hospital_manager@xyz.com      | Password@2025 |
| Inner Pantry Staff   | hospital_pantry@xyz.com       | Password@2025 |
| Delivery Personnel   | hospital_delivery@xyz.com     | Password@2025 |

---

## Future Enhancements
- Integrate TypeScript for improved code quality.
- Add analytics (e.g., number of meals delivered per day).
- Implement push notifications for delayed deliveries.

---

## Author
**Your Name**  
[MERN Stack Developer](https://abusaiyedjoy.netlify.app)

---

## Contact
For any concerns or questions, feel free to reach out via email: abusaiyedjoy1@gmail.com
