Phase 2 Summary – Technology & Architecture Design
🔧 Architecture Workflow:
CDSCO (Central Drug Standard Control Organization):

Approves or denies manufacturing requests.

Supplier → Manufacturer: Supplies drug components.

Manufacturer:

Requests approval.

Produces drugs.

Sends drugs to distributors or repackagers.

Repackager: Repackages and forwards drugs to distributors.

Primary Distributor → Secondary Distributor: Passes drugs for further distribution.

Distributors → Hospitals → Patients: Final drug delivery chain.

🔄 Flow of Information:
Each stakeholder has defined roles and interactions, all of which are recorded immutably using blockchain, enhancing traceability and trust.

💻 Technology Stack (Frontend):
Languages & Tools:

HTML5, CSS3, JavaScript

EJS (for templating)

jQuery & Bootstrap (for UI/UX)

Visual Studio Code (v1.68) for development and debugging

Frontend Features:

Add/Search medicines

Track location

View drug history

Update status dynamically

🔐 Security & Transparency:
The system ensures traceability from manufacturing to patient.

Prevents entry of counterfeit drugs via unauthorized sources (“bad factories”).

Blockchain guarantees tamper-proof records and real-time verification.
