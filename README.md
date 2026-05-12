# Jewellery Billing System

A desktop-based Jewellery Billing System developed using Visual Basic 6.0. The project is designed for jewellery shop management, including customer records, supplier details, product entry, product purchase orders, customer orders, sales invoices, billing, and printable reports.

## Features

- User login system
- MDI-based main dashboard
- Customer details management
- Supplier details management
- Jewellery product entry
- Product purchase order management
- Customer order management
- Product sales invoice generation
- Search invoice by order number
- Billing calculation support
- Product and customer data handling using ADODB
- Oracle database connectivity
- DataGrid-based record display
- Multiple printable Data Reports
- Jewellery shop branding and image-based UI assets
- Logout option from the main dashboard

## Tech Stack

- Visual Basic 6.0
- ADODB
- Oracle Database
- Microsoft Data Report Designer
- VB6 Forms
- VB6 Modules
- OCX Controls

## Project Structure

```text
jewellery billing system/
├── CUSTOMER.frm
├── CUSTOMER.frx
├── cust_ord_frm.frm
├── cust_ord_frm.frx
├── Form1.frm
├── Form1.frx
├── Form3.frm
├── Form3.frx
├── Form4.frm
├── Form4.frx
├── JwelleryproductEntry.frm
├── JwelleryproductEntry.frx
├── MDIForm1.frm
├── MDIForm1.frx
├── Order _PRO_PURCHASE.frm
├── Order _PRO_PURCHASE.frx
├── Prod_Order.frm
├── Prod_Order.frx
├── saleinv.frm
├── saleinv.frx
├── SUPP_ENTRY.frm
├── SUPP_ENTRY.frx
├── Module1.bas
├── DataEnvironment1.Dsr
├── DataEnvironment1.DCA
├── DataReport1.Dsr
├── DataReport1.dsx
├── DataReport1.DCA
├── DataReport2.Dsr
├── DataReport2.dsx
├── DataReport2.DCA
├── DataReport3.Dsr
├── DataReport3.dsx
├── DataReport3.DCA
├── DataReport4.Dsr
├── DataReport4.dsx
├── DataReport4.DCA
├── DataReport5.Dsr
├── DataReport5.dsx
├── DataReport5.DCA
├── DataReport6.Dsr
├── DataReport6.dsx
├── DataReport6.DCA
├── DataReport7.Dsr
├── DataReport7.dsx
├── DataReport7.DCA
├── DataReport8.Dsr
├── DataReport8.dsx
├── DataReport8.DCA
├── DataReport9.Dsr
├── DataReport9.dsx
├── DataReport9.DCA
├── DataReport10.Dsr
├── DataReport10.dsx
├── DataReport10.DCA
├── DataReport11.Dsr
├── DataReport11.dsx
├── DataReport11.DCA
├── jwelleryBillingSystem.vbp
├── jwelleryBillingSystem.vbw
├── *.jpg
└── README.md

Requirements
Visual Basic 6.0 IDE
Oracle Database
Oracle client/provider support
Microsoft ActiveX Data Objects 2.0 Library
Microsoft Data Report Designer v6.0
Required VB6 OCX controls:
MSADODC.OCX
MSDATGRD.OCX
DBGRID32.OCX
TABCTL32.OCX
MSCOMCT2.OCX
How to Run
Clone the repository:
git clone https://github.com/your-username/Jewellery-Billing-System.git
cd Jewellery-Billing-System
Open the project file in Visual Basic 6.0:
jwelleryBillingSystem.vbp
Configure the Oracle database connection in Module1.bas.

Run the project from the VB6 IDE.

Database Connection
The project uses ADODB connection with Oracle provider.

Before uploading publicly, remove or change any real database username/password from Module1.bas.

Example:

c.Open "Provider=MSDAORA.1;User ID=your_username/your_password;Persist Security Info=True"
Important Note
Do not upload temporary VB files, compiled files, or local machine-specific files to GitHub.

Also remove private database credentials before uploading the project publicly.

Author
Created by Sachin.


**Recommended `.gitignore`**

```gitignore
# VB6 temporary files
*.tmp
*.log
*.vbw

# Compiled output
*.exe
*.dll
*.ocx
*.obj
*.pdb

# Visual SourceSafe / local source control files
MSSCCPRJ.SCC
*.scc

# OS files
.DS_Store
Thumbs.db

# IDE folders
.vscode/
.idea/

# Environment / private config
.env
Files You Should Upload

Upload these:

*.frm
*.frx
*.bas
*.vbp
*.Dsr
*.dsx
*.DCA
*.jpg
README.md
.gitignore
Do Not Upload These

*.tmp
*.log
*.exe
MSSCCPRJ.SCC
GitHub About Section

Description:
A Visual Basic 6 jewellery billing system for customer management, supplier records, product entry, purchase orders, sales invoices, billing, Oracle database connectivity, and printable reports.

Topics:
jewellery-billing-system vb6 visual-basic-6 oracle-database adodb billing-system inventory-management sales-invoice desktop-application jewellery-management-system
