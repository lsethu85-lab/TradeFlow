# LC Document Checking Dashboard

A professional **Letter of Credit (LC) Document Checking Dashboard** built with HTML, CSS, and JavaScript.

This dashboard is designed for trade finance operations teams to manage LC cases, upload documents, monitor compliance, track discrepancies, manage tasks, review deadlines, and view executive-level KPIs.

---

## 📌 Overview

The LC Document Checking Dashboard provides a browser-based workspace for managing Letter of Credit operations.

It includes:

- LC case creation and tracking
- Document upload using drag-and-drop or file browser
- Compliance checking workspace
- Discrepancy monitoring
- Task management
- Calendar and deadline tracking
- Reports and analytics
- Audit trail
- Settings
- About Dashboard guide
- Tooltip help icons for feature explanation

The latest version includes a fixed and improved **Document Upload Center**, including a visible **Browse Files** button, drag-and-drop support, unassigned uploads, and document metadata tracking.

---

## 🚀 Features

### 1. Executive Dashboard

The main dashboard provides a high-level view of LC operations.

Key metrics include:

- Total LC Cases
- Pending Review
- Approved Cases
- Discrepancies
- Total LC Exposure
- Expiring in 30 Days
- Documents Pending
- Compliance Pass Rate
- Average Processing Time
- At-Risk LC Cases
- Top Issuing Bank
- SLA Breached Cases

---

### 2. LC Cases Management

Create and manage Letter of Credit records.

Each LC case includes:

- LC Number
- Issue Date
- Issuing Bank
- Advising Bank
- Applicant
- Beneficiary
- Amount
- Currency
- Expiry Date
- Status
- Description

Supported LC statuses:

- Draft
- Pending Review
- Approved
- Active
- Closed

---

### 3. Document Upload Center

Upload and manage LC-related documents.

Supported actions:

- Select an LC Case
- Drag and drop files into the upload zone
- Click the upload zone to select files
- Use the **Browse Files** button
- Upload files without selecting an LC case as `UNASSIGNED`
- View uploaded document metadata
- Delete uploaded document records
- Show all uploaded documents

The system can detect document categories such as:

- Commercial Invoice
- Packing List
- Bill of Lading
- Insurance Certificate
- Certificate of Origin
- PDF Document
- Word Document
- Spreadsheet
- Image Document
- Supporting Document

> Note: This prototype stores uploaded document metadata locally in the browser. It does not upload files to a server.

---

### 4. Compliance Checker

The Compliance Checker section is designed to review LC cases against internal checking requirements.

It can be used to track:

- LC terms review
- Document readiness
- Compliance status
- Last checked information
- Operational validation results

---

### 5. Discrepancy Dashboard

Track and manage LC document discrepancies.

Examples of discrepancies include:

- Missing documents
- Incorrect invoice details
- Shipment date mismatch
- Beneficiary name mismatch
- Amount or currency mismatch
- Late presentation
- Missing insurance certificate
- Incorrect bill of lading details

Discrepancies can be filtered by severity:

- Critical
- Major
- Minor

---

### 6. Task Management

Create and manage operational tasks.

Each task includes:

- Task title
- Description
- Assigned person
- Priority
- Due date
- Related LC case
- Status

Supported task statuses:

- To Do
- In Progress
- Completed
- Cancelled

Supported priorities:

- High
- Medium
- Low

---

### 7. Calendar and Deadlines

The calendar section helps monitor LC-related events and deadlines.

Examples:

- LC expiry date
- Shipment deadline
- Document presentation period
- Follow-up date
- Review deadline

---

### 8. Reports and Analytics

The reports section provides management-level insights.

Includes:

- Total Revenue
- Processing Rate
- Average Processing Time
- Performance Report
- Target vs Actual comparison
- Variance tracking

---

### 9. Audit Trail

The audit trail records key system activities.

Examples:

- LC case created
- Task created
- Document uploaded
- Document deleted
- LC case deleted

Audit data includes:

- Date and time
- User
- Action
- Entity
- Changes

---

### 10. About Dashboard

The **About Dashboard** page explains how to use the system.

It includes:

- Recommended LC workflow
- Feature-by-feature explanation
- Dashboard usage guide
- Document upload instructions
- Compliance workflow
- Task workflow
- Reporting explanation
- Important prototype notes

---

### 11. Help Tooltip Icons

Small `?` help icons are available across the dashboard.

They explain:

- Menu items
- Dashboard cards
- Buttons
- Table headers
- Form labels
- KPI sections
- Workflow panels

Hover over a `?` icon to see what the feature does.

---

### 12. Global Search

The search box in the header can filter visible table rows.

You can search by:

- LC Number
- Applicant
- Beneficiary
- Bank
- Status
- Amount
- Document name
- Task title

---

## 🛠️ Technologies Used

This project is built using:

- HTML5
- CSS3
- Vanilla JavaScript
- Chart.js
- Remix Icon
- Flatpickr
- Browser localStorage

No backend server is required for this prototype.

---

## 📂 Project Structure

```text
lc-dashboard/
│
├── index.html
├── README.md
└── screenshots/
    ├── dashboard.png
    ├── document-upload.png
    └── about-dashboard.png
```

Recommended final HTML file name:

```text
index.html
```

If you downloaded the latest generated version, rename:

```text
lc_dashboard_upload_fixed_index.html
```

to:

```text
index.html
```

before publishing to GitHub Pages.

---

## ▶️ How to Run Locally

### Option 1: Open Directly

1. Download the HTML file.
2. Rename it to `index.html`.
3. Double-click the file.
4. It will open in your browser.

### Option 2: Use VS Code Live Server

1. Open the project folder in Visual Studio Code.
2. Install the **Live Server** extension.
3. Right-click `index.html`.
4. Select **Open with Live Server**.

---

## 🌐 How to Deploy on GitHub Pages

1. Create a new GitHub repository.
2. Upload the following files:

```text
index.html
README.md
```

3. Go to repository **Settings**.
4. Open **Pages**.
5. Under **Source**, select:

```text
Deploy from a branch
```

6. Choose:

```text
main / root
```

7. Click **Save**.
8. GitHub will generate a public website URL.

Example:

```text
https://your-username.github.io/lc-dashboard/
```

---

## 💾 Data Storage

This dashboard uses browser `localStorage`.

Stored locally:

- LC cases
- Tasks
- Audit logs
- Uploaded document metadata
- Theme preference

Not stored on a server:

- Actual uploaded file content
- User passwords
- Sensitive banking data

---

## ⚠️ Important Disclaimer

This dashboard is a prototype and demonstration tool.

It should not be used for production-level banking, financial, or legal processing without:

- Secure backend storage
- Authentication
- Role-based access control
- Server-side audit logging
- Data encryption
- User permission controls
- File scanning
- Compliance validation
- Security review
- Legal review

Users must independently verify all LC, compliance, financial, and document information before making operational, financial, or legal decisions.

---

## 🔐 Security Notes

For a production version, consider adding:

- Login and authentication
- User roles and permissions
- Encrypted database
- Secure document storage
- Server-side audit trail
- Document version control
- Maker-checker approval workflow
- File type validation
- Malware scanning
- Data backup
- API integration with core banking or trade finance systems

---

## 🧭 Recommended Workflow

```text
1. Create LC Case
2. Upload Documents
3. Review Compliance
4. Identify Discrepancies
5. Assign Tasks
6. Resolve Issues
7. Approve LC Case
8. Monitor Deadlines
9. Review Reports
10. Check Audit Trail
```

---

## 📸 Suggested Screenshots

For a better GitHub repository, add screenshots such as:

```text
screenshots/dashboard.png
screenshots/document-upload.png
screenshots/lc-cases.png
screenshots/about-dashboard.png
```

Then include them in this README later:

```markdown
![Dashboard](screenshots/dashboard.png)
![Document Upload](screenshots/document-upload.png)
```

---

## 🧩 Future Enhancement Ideas

Possible future improvements:

- Backend database integration
- User login
- Role-based access
- Real file storage
- Document preview
- PDF OCR extraction
- AI-powered document checking
- UCP 600 rule validation
- ISBP checklist integration
- SWIFT message support
- Maker-checker approval workflow
- Email notifications
- Export to Excel/PDF
- Dashboard filters
- Multi-currency conversion
- Country risk dashboard
- Bank exposure analytics
- Document version comparison

---

## 👤 Author

Built by **Sethu**.

---

## 📄 License

This project is provided for demonstration and educational purposes.

You may customize it for internal prototype use.

For commercial or production banking use, perform proper security, compliance, and legal reviews.

---

## ✅ Current Version

```text
Version: 1.0
Status: Prototype
Latest HTML: lc_dashboard_upload_fixed_index.html
```

---

## 🙌 Contribution

If you want to improve this dashboard:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.

Suggested contribution areas:

- UI improvements
- Better validation
- Export features
- Backend integration
- Document preview
- Compliance rule engine
- Accessibility improvements
