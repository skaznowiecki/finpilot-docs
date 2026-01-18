# Facturas - Product Documentation

## Table of Contents
1. [Introduction](#introduction)
2. [Core Features](#core-features)
3. [User Flows](#user-flows)
4. [Feature Details](#feature-details)

---

## Introduction

### What is Facturas?

Facturas is an intelligent invoice management platform designed to help companies streamline their invoice processing, tracking, and management workflows. The system handles invoices from both external suppliers and internal employees, providing a centralized solution for invoice lifecycle management.

### Who is it for?

Facturas is designed for companies of all sizes that need to:
- Process and manage invoices from multiple suppliers
- Track employee expense invoices
- Automate invoice data extraction and entry
- Maintain organized records of financial documents
- Monitor invoice status and payment schedules
- Generate insights about spending patterns

### Key Value Propositions

**Intelligent Automation**
- Automatically extract invoice data from PDFs and images using AI
- Process invoices received via email without manual intervention
- Detect and prevent duplicate invoices

**Time Savings**
- Eliminate manual data entry with AI-powered extraction
- Automatically categorize and organize invoices
- Streamline approval workflows

**Complete Visibility**
- Real-time dashboard with key metrics and insights
- Track invoice status from receipt to payment
- Monitor upcoming payment obligations
- Analyze spending trends over time

**Flexible Organization**
- Support multiple organizations within a company
- Categorize invoices and parties with custom tags
- Organize by supplier, employee, or custom criteria

**Secure Collaboration**
- Role-based access control for team members
- Comments and document attachments for collaboration
- Complete audit trail of all changes

---

## Core Features

### 1. Invoice Management

The heart of Facturas is comprehensive invoice management that handles the entire invoice lifecycle from receipt to payment.

**Invoice Processing**
- Upload invoices manually as PDF or image files
- Automatic data extraction using AI (invoice number, dates, amounts, supplier information)
- Automatic duplicate detection to prevent processing the same invoice twice
- Support for multiple invoice types (A, B, C, etc.)
- Automatic matching with existing suppliers or creation of new supplier records

**Invoice Organization**
- View all invoices in a searchable, filterable list
- Filter by status, supplier, date range, amount, or custom tags
- Sort by any field for easy organization
- Pagination for handling large volumes of invoices

**Invoice Details**
- View complete invoice information including line items
- See associated supplier or employee information
- Track invoice status and approval state
- View payment dates and due dates
- Access original invoice file and related documents

**Invoice Status Tracking**
- **Processing Status**: PENDING, VALIDATED, DUPLICATE, ERROR
- **Business State**: PENDING, PRE_APPROVED, APPROVED, REJECTED, PAID
- Visual indicators for quick status identification
- Automatic status updates based on workflow actions

**Invoice Editing**
- Update invoice information after initial processing
- Correct any errors in extracted data
- Add or modify line items
- Update payment dates and status

**Bulk Operations**
- Import multiple invoices from Excel or CSV files
- Export invoices to Excel or CSV for external analysis
- Apply filters before export for targeted data extraction

**Invoice Documents**
- Attach multiple documents to each invoice
- Support for files, text notes, or web links
- Organize documents with tags
- Secure access to all invoice-related documents

**Invoice Comments**
- Add comments to invoices for team collaboration
- Edit or delete comments as needed
- Attach files to comments for additional context
- Track who made each comment and when

**Invoice History**
- Complete audit trail of all changes to invoices
- See who made changes and when
- Track field-level changes for compliance
- View full history of status transitions

### 2. Email Integration

Automate invoice processing by receiving invoices directly via email.

**Email Configuration**
- Configure one or more email addresses to receive invoices
- Each company can have multiple email destinations
- Enable or disable email destinations as needed

**Automatic Processing**
- Forward invoices to your configured email address
- System automatically detects PDF and image attachments
- AI validates that attachments are actual invoices
- Invoices are automatically extracted and created in the system
- No manual upload required

**Email History**
- View all processed emails
- See which emails contained invoices
- Track which invoices were extracted from each email
- View original email content when needed

### 3. Supplier & Employee Management (Parties)

Manage all parties that send invoices - whether external suppliers or internal employees.

**Party Types**
- **Suppliers**: External vendors providing goods or services
- **Employees**: Internal staff members submitting expense invoices

**Party Information**
- Store complete contact information (name, email, phone, address)
- Manage tax identification numbers (CUIT, CUIL, DNI, passport, etc.)
- Track employment status for employees (active, inactive, terminated)
- Store employment dates for employees
- Add custom fields for additional information

**Bank Account Management**
- Store multiple bank accounts per party
- Record bank details (account number, SWIFT code, branch code)
- Designate primary account for payments
- Track account validity dates
- Store bank address and correspondent bank information

**Party Organization**
- Categorize parties with custom tags
- Filter parties by type, status, or tags
- Search parties by name, tax ID, or email
- Export party data for external use

**Party Onboarding**
- Onboard new parties to the system
- Link party records to user accounts when applicable
- Track onboarding status and dates

### 4. Tag Management

Organize invoices and parties with a flexible tagging system.

**Tag Types**
- **Party Tags**: Categorize suppliers and employees
- **Invoice Tags**: Categorize invoices for easy filtering

**Tag Features**
- Create custom tags with descriptive names
- Assign colors to tags for visual organization
- Assign multiple tags to any invoice or party
- Filter and search by tags
- Manage tags centrally

**Use Cases**
- Tag invoices by project, department, or expense category
- Tag suppliers by vendor type or relationship
- Tag employees by department or role
- Create custom organizational schemes

### 5. Organization Management

Support multiple organizations or business units within a single company account.

**Multi-Organization Support**
- Create and manage multiple organizations
- Assign invoices to specific organizations
- Track invoices separately by organization
- Upload organization-specific logos for branding

**Organization Features**
- Each organization maintains its own invoice records
- Filter and view invoices by organization
- Organization-level reporting and analytics
- Soft delete support for maintaining historical data

### 6. Dashboard & Analytics

Get instant insights into your invoice operations with comprehensive dashboards.

**Key Metrics**
- **Pending Invoices**: Count of invoices awaiting approval or action
- **New Invoices Today**: Number and total amount of invoices received today
- **New Suppliers Today**: Count of new suppliers added today

**Visual Analytics**
- **Weekly Invoice Trends**: View invoice volume and amounts over the last 12 weeks
- **Upcoming Invoices**: See invoices due for payment in the next 7 days
- **Top Providers**: Identify suppliers with highest invoice volume or amounts
- Interactive charts for exploring data

**Period Filtering**
- Filter analytics by time period (last 30 days, last 90 days, custom ranges)
- Compare periods to identify trends
- Export analytics data for external reporting

### 7. User Management

Manage team members and their access to the system.

**User Operations**
- Add new users to your company
- Invite users via email
- View all users in your company
- Update user information
- Activate or deactivate user accounts
- Remove users when needed

**User Types**
- **Administrator**: Full access to all features and settings
- **Party User**: Limited access, typically linked to a specific supplier or employee record

**User Profiles**
- View and edit user profile information
- Change passwords
- Update contact information

### 8. Role & Permission Management

Control what each user can do with granular permission management.

**Role System**
- Create custom roles for your company
- Use predefined system roles
- Assign multiple permissions to each role
- Assign roles to users

**Permission System**
- Granular permissions for each feature and action
- Examples: create invoices, view invoices, manage users, manage settings
- Permissions control both what users see and what they can do
- UI automatically adapts based on user permissions

**Common Roles**
- **Administrator**: Full access to everything
- **Invoice Manager**: Can manage invoices but not users
- **Viewer**: Can view invoices but not edit
- **Custom Roles**: Create roles tailored to your organization

### 9. Company Settings

Configure your company's preferences and information.

**Company Information**
- Company name and description
- Tax identification number (CUIT)
- Company size
- Upload company logo

**Payment Configuration**
- Set default payment terms (days from invoice reception to payment)
- Configure payment date calculation rules

**Customization**
- Add custom fields for invoices or parties
- Configure default values
- Set up company-specific workflows

### 10. Subscription Management

Manage your subscription and billing.

**Subscription Status**
- View current subscription status (Trial, Active, etc.)
- See subscription period and renewal dates
- Track trial period remaining

**Payment Methods**
- Add and manage payment methods
- Set default payment method
- Update payment information

**Subscription Management**
- View subscription details
- Cancel subscription if needed
- Track usage metrics

### 11. Onboarding

Guided setup process for new users.

**Initial Setup**
- Create your company account
- Enter company information
- Configure initial settings
- Watch demo videos to learn the system

**First Steps**
- Guided tour of key features
- Create your first invoice
- Add your first supplier
- Configure email integration

### 12. Contact & Support

Get help when you need it.

**Contact Forms**
- General contact form for questions
- Sales inquiries for pricing information
- Professional plan requests for enterprise features
- All contacts are tracked and responded to

---

## User Flows

### New User Registration & Onboarding

1. **Registration**
   - User creates account with email and password
   - Email verification (if required)

2. **Onboarding**
   - User enters company information (name, tax ID, size)
   - Configures payment terms
   - Watches demo video
   - Completes guided tour

3. **First Actions**
   - User is ready to start using the system
   - Can create invoices, add suppliers, or configure email

### Manual Invoice Processing Flow

1. **Upload Invoice**
   - User navigates to invoice creation page
   - Uploads PDF or image file
   - System generates secure upload URL

2. **AI Extraction**
   - System processes file with AI
   - Extracts invoice number, dates, amounts, supplier info
   - Identifies line items and taxes

3. **Review & Confirm**
   - User reviews extracted data
   - Can edit any fields if needed
   - Confirms invoice creation

4. **Invoice Created**
   - Invoice is saved with VALIDATED status
   - Supplier is created or matched automatically
   - Invoice appears in invoice list
   - User can add tags, documents, or comments

### Email-Based Invoice Processing Flow

1. **Email Reception**
   - Supplier sends invoice to configured email address
   - Email is received and queued for processing

2. **Automatic Detection**
   - System checks email for PDF or image attachments
   - AI validates that attachments are invoices
   - Non-invoice attachments are ignored

3. **Automatic Processing**
   - Invoice data is extracted automatically
   - Supplier is created or matched
   - Invoice is created in system

4. **Notification**
   - User sees new invoice in dashboard
   - Can review and approve invoice
   - System tracks which email the invoice came from

### Invoice Approval Workflow

1. **Invoice Received**
   - Invoice enters system with PENDING state
   - Appears in pending invoices list

2. **Review**
   - User reviews invoice details
   - Checks line items and amounts
   - Verifies supplier information
   - Adds comments or documents if needed

3. **Approval Decision**
   - **Approve**: Invoice moves to APPROVED state
   - **Pre-approve**: Invoice moves to PRE_APPROVED state for final review
   - **Reject**: Invoice moves to REJECTED state with reason

4. **Payment**
   - When invoice is paid, state changes to PAID
   - Payment date is recorded
   - Invoice is archived

### Party Management Flow

1. **Add Party**
   - User navigates to parties section
   - Clicks "Add Supplier" or "Add Employee"
   - Enters party information (name, tax ID, contact info)

2. **Optional Details**
   - Add bank account information
   - Assign tags for categorization
   - Add custom fields

3. **Save**
   - Party is created in system
   - Can immediately be used when creating invoices
   - Appears in party list

4. **Manage**
   - Edit party information as needed
   - Add multiple bank accounts
   - Update employment status (for employees)
   - View all invoices from this party

### User & Permission Management Flow

1. **Create Role**
   - Administrator navigates to roles section
   - Creates new role with descriptive name
   - Selects permissions for the role

2. **Invite User**
   - Administrator invites user via email
   - User receives invitation email

3. **User Accepts**
   - User clicks link in email
   - Creates password
   - Completes profile

4. **Assign Role**
   - Administrator assigns role to user
   - User immediately has appropriate permissions
   - UI adapts to show only permitted features

---

## Feature Details

### Invoice States & Status Explained

**Processing Status** (Technical validation)
- **PENDING**: Invoice is being processed or awaiting validation
- **VALIDATED**: Invoice has been successfully processed and validated
- **DUPLICATE**: Invoice matches an existing invoice and was not created
- **ERROR**: Processing failed due to an error

**Business State** (Workflow status)
- **PENDING**: Invoice is awaiting review or approval
- **PRE_APPROVED**: Invoice has been pre-approved but needs final approval
- **APPROVED**: Invoice has been approved and is ready for payment
- **REJECTED**: Invoice has been rejected with a reason
- **PAID**: Invoice has been paid

### Tag System Use Cases

**Invoice Tags**
- Project-based: Tag invoices by project code
- Department: Tag by department or cost center
- Expense type: Tag by expense category
- Priority: Tag urgent or important invoices
- Status: Custom status tags beyond system states

**Party Tags**
- Vendor type: Distinguish between different supplier categories
- Relationship: Tag strategic partners, preferred vendors
- Location: Tag by geographic region
- Department: For employees, tag by department

### Dashboard Metrics Explained

**Pending Invoices Count**
- Shows how many invoices need attention
- Helps prioritize daily work
- Updates in real-time

**New Invoices Today**
- Tracks daily invoice volume
- Shows both count and total amount
- Helps monitor business activity

**New Suppliers Today**
- Identifies new business relationships
- Helps track vendor onboarding
- Useful for procurement insights

**Weekly Trends**
- Shows invoice volume over time
- Helps identify seasonal patterns
- Useful for cash flow planning

**Upcoming Invoices**
- Shows invoices due in next 7 days
- Helps with cash flow management
- Enables proactive payment planning

**Top Providers**
- Identifies largest suppliers by volume or amount
- Helps with vendor relationship management
- Useful for negotiating better terms

### Multi-Organization Benefits

**Use Cases**
- Companies with multiple subsidiaries
- Separate business units or divisions
- Different brands or product lines
- Geographic separation

**Benefits**
- Separate financial tracking per organization
- Organization-specific reporting
- Maintain separate supplier lists
- Independent invoice management

### Email Integration Benefits

**Time Savings**
- No manual file uploads required
- Automatic processing while you work
- Suppliers send invoices directly to system

**Error Reduction**
- No risk of missing invoices
- Automatic duplicate detection
- Consistent processing

**Convenience**
- Suppliers use familiar email workflow
- No training required for suppliers
- Works with any email client

### AI-Powered Extraction Capabilities

**Extracted Fields**
- Invoice number
- Invoice date and due date
- Supplier name and tax ID
- Line items with descriptions, quantities, and prices
- Subtotal, taxes, and total amounts
- Invoice type (A, B, C, etc.)
- Point of sale information

**Accuracy**
- High accuracy with AI validation
- Manual review and correction available
- Learning improves over time

**Supported Formats**
- PDF invoices
- Image files (JPG, PNG)
- Scanned documents

---

## Getting Started

### For New Users

1. **Sign Up**: Create your account
2. **Complete Onboarding**: Enter company information
3. **Add Your First Supplier**: Start building your party database
4. **Upload Your First Invoice**: Try the AI extraction
5. **Configure Email**: Set up automatic processing
6. **Invite Team Members**: Add users and assign roles
7. **Explore Dashboard**: Review your metrics and insights

### For Administrators

1. **Configure Settings**: Set up company preferences
2. **Create Roles**: Define permission sets for your team
3. **Invite Users**: Add team members with appropriate roles
4. **Set Up Email**: Configure email destinations
5. **Create Tags**: Set up your organizational tags
6. **Review Dashboard**: Monitor system activity

### Best Practices

**Invoice Management**
- Review extracted data for accuracy
- Add tags immediately for better organization
- Use comments to track approval decisions
- Keep documents attached for reference

**Party Management**
- Complete party profiles with all information
- Add bank accounts for payment processing
- Use tags to organize parties effectively
- Keep contact information up to date

**Team Collaboration**
- Use comments for communication
- Attach relevant documents
- Leverage tags for visibility
- Review changelog for audit purposes

**Email Integration**
- Use dedicated email addresses for invoices
- Monitor email processing regularly
- Review extracted invoices for accuracy
- Keep email destinations active

---

## Support & Resources

### Getting Help

- Use the contact forms in the application
- Review the dashboard for system status
- Check email processing history for issues
- Review invoice changelog for audit trails

### Feature Requests

- Submit feature requests through contact forms
- Professional plan users have priority support
- Regular updates add new features based on feedback

---

*This documentation covers the core features and capabilities of Facturas. For technical implementation details, please refer to the API documentation.*
