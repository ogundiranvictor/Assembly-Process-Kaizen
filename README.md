# Assembly Process Kaizen (APK) Software Overview

The Assembly Process Kaizen (APK) software is utilized within automobile assembly plants to streamline and manage operations across four primary divisions:

### Logistics
The logistics division orchestrates the movement of necessary parts to the production line, encompassing components like:
- Chassis
- Cargo
- Cabin
- Engine
- Rear Axle, etc.

This division meticulously records and comments on all items that enter the production line on a daily basis.

### Production
The production department is segmented into two main groups based on the type of vehicle to be assembled:
1. **Stations**
   - Station One
   - Station Two
   - Station Three
   - Station Four

2. **Trims**
   - Trim One
   - Trim Two
   - Trim Three
   - Trim Four
   - Trim Five
   - Trim Six
   - Trim Seven

Each station and trim stage possesses its dedicated container housing comprehensive instructions for every stage of production. These instructions include:
- Timer: Records the duration spent on each task.
- Password: Quality control officers verify proper fitting of essential parts before allowing progression to subsequent stages.
- Body Comment: Enables quality control officers to provide feedback on the vehicle.
- Online and Offline Status: Indicates the vehicle's current status on the production line.
- Submit Button: Initiates the saving of input data into a text file and sends this information to the spreadsheet API for record-keeping.

Additionally, the supervisor must approve vehicles before transitioning them to another division.

### Quality Control
The Quality Control module encompasses various tests and inspections such as:
1. Underbody Test (U/B)
2. Wheel Alignment (W/A)
3. Side Slip Test (S/T)
4. Thrust Angle Test (T/T)
5. Horn Test (H/T)
6. Headlamp Aiming Test (H/AT)
7. Brake Test (B/T)
8. Dynamometer Test (D/T)
9. Shower Test (S/T)
10. Road Test (R/T)

### Quality Assurance
The Quality Assurance Officer oversees the final stage of production and manages:
1. Quality Track Management (QTM)
2. Process Audit
3. Job Card
4. Delivery Note

**Technology Stack:**
- Programming Languages: JavaScript
- **Database:** Google Drive, Spreadsheet API
- **Tools:** HTML, CSS, VSCode

This encapsulates the current functionality of the Assembly Process Kaizen (APK) Software, with plans for additional features in the future.
