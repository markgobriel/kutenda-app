# KUTENDA 🚍🎟️
A reward point system app designed for bus drivers in Cameroon, helping encourage frequent stops at Kutenda Centre. The app rewards drivers with points, promoting increased foot traffic and generating more profit for local businesses.

## Goal of the App 🎯
Kutenda's main goal is to print tickets with reward points for bus drivers who make verified stops. By rewarding drivers, the app entices them to stop at the Kutenda Centre, benefiting the business through increased customer visits. The reward system is designed to ensure fairness, prevent fraud, and encourage consistent stops during the day and night.

## How the App Works 🛠️
- The driver stops at the Kutenda Centre, and the user scans the bus's license plate using the app.
- To prevent fraud, the user takes a picture of the bus, and the app compares the image to the scanned license plate.
- If the plate is damaged or unrecognizable, the user can enter the plate manually, with manual verification to ensure accuracy.
- The license plate is assigned to a specific bus category, and the driver is linked to that bus.
- Each driver can be assigned multiple license plates but cannot be awarded a second ticket within 3-4 hours of receiving their last one.
- The printed ticket includes the following information:
  - Driver's name and details
  - Bus information (size and category)
  - License plate
  - Date and time
  - Ticket number
  - Ticket value
- Ticket values vary based on the size of the bus:
  - **6 AM - 6 PM:** Gros Porteur (2000 CFA), Costail (1500 CFA), Hyasse (1000 CFA), Picnic (500 CFA)
  - **6 PM - 6 AM:** Gros Porteur (2000 CFA), Costail (1000 CFA), Hyasse (500 CFA), Picnic (0 CFA)
- Each ticket tracks the number of times the driver has received a ticket. When a driver reaches 15 tickets, they earn a bonus:
  - Gros Porteur: 1500 CFA
  - Costail: 1000 CFA
  - Hyasse: 500 CFA
- During nighttime hours (6 PM - 6 AM), drivers are also eligible for a free coffee ticket, printed separately. This ticket includes the same information as the main reward ticket.
- All ticket data is saved in the stats report section, which tracks daily, weekly, and monthly activity. Only the director has access to this report.
- The app’s data structure includes four bus companies, each with a set of plates and drivers. Each driver can be assigned to multiple plates; all data is tracked in the app's report system.
- Once the ticket is printed, the app automatically saves it for future reference.

## Tech Stack 🛠️
* Application Design: Figma
* Backend: N/A
* Frontend: Kotlin

## Standout Features ✨
- The app ensures drivers cannot receive two tickets in less than 3-4 hours.
- All data is saved securely, and reports are accessible to the director for auditing and analysis.
- Fraud prevention measures include manual verification of license plates and images.

## The Team 🧠
| Member  | Position | Responsibilities |
| ------------- | ------------- | ------------- |
| Enzo Lotchuang  | Developer  | * |
| Mark Gobriel  | Developer & UX Designer  | * |
