# Architecture

## Identity & Access (Entra ID)
- Users created per department and location
- Security Groups:
  - Finance_Group
  - Operations_Group
  - CustomerService_Group
- Conditional Access: MFA required for all users
- SSPR enabled for all users
- PIM: admin roles eligible + approval required

## Collaboration
- Teams per department + channels (General, Projects, Announcements)
- Exchange Online shared mailbox: support@company.com

## Document Management
- SharePoint Team Sites:
  - Finance Site
  - Operations Site
  - Customer Service Site
- Permissions applied by security groups
- Versioning + metadata (“Document Type”)

## Security & Compliance
- DLP blocks external sharing of sensitive info in SharePoint/OneDrive/Teams
- Conditional Access blocks unmanaged devices
- Defender phishing simulation + reporting

## Automation
- Finance library upload triggers approval in Teams

## Reporting
- Power BI dashboard from SharePoint-hosted Excel

## Location-based Admin
- Administrative Units: Nigeria_Users, America_Users, India_Users
