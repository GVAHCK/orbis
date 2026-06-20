# FlowForge ERP Design Audit Report

## 1. Screen Inventory & Theme Coverage
| Module | Screen | Light Mode | Dark Mode | Status |
| :--- | :--- | :---: | :---: | :--- |
| **Auth** | Login | ❌ | ❌ | Missing Both |
| | Forgot Password | ❌ | ❌ | Missing Both |
| **General** | Dashboard | ❌ | ❌ | Missing Both |
| | Executive Dashboard | ✅ (S12) | ❌ | Missing Dark |
| | Digital Twin Dashboard | ✅ (S18) | ✅ (S3) | Consistent |
| | Notification Center | ❌ | ❌ | Missing Both |
| | Settings | ❌ | ❌ | Missing Both |
| | Profile | ❌ | ❌ | Missing Both |
| | Help Center | ❌ | ❌ | Missing Both |
| **Products** | Product List | ❌ | ❌ | Missing Both |
| | Product Details | ❌ | ❌ | Missing Both |
| | Product Create | ❌ | ❌ | Missing Both |
| **Inventory** | Inventory Dashboard | ✅ (S10) | ❌ | Missing Dark |
| | Inventory Ledger | ❌ | ❌ | Missing Both |
| | Movement Timeline | ❌ | ❌ | Missing Both |
| **Sales** | Sales Order List | ✅ (S15) | ✅ (S26) | Consistent |
| | Sales Order Details | ✅ (S19) | ❌ | Missing Dark |
| | Create Sales Order | ✅ (S9) | ❌ | Missing Dark |
| | Customer Management | ❌ | ❌ | Missing Both |
| **Purchase** | Purchase Order List | ✅ (S5) | ✅ (S14) | Consistent |
| | PO Details | ✅ (S31) | ❌ | Missing Dark |
| | Vendor Management | ✅ (S21) | ✅ (S27) | Consistent |
| | Vendor Profile | ✅ (S24) | ❌ | Missing Dark |
| | Procurement Recommendations | ✅ (S29) | ✅ (S8) | Consistent |
| | Purchase Receipt | ✅ (S7) | ❌ | Missing Dark |
| **Manufacturing** | Command Center | ✅ (S16) | ✅ (S20) | Consistent |
| | Manufacturing Orders | ✅ (S17) | ❌ | Missing Dark |
| | Manufacturing Kanban | ✅ (S13) | ✅ (S22) | Consistent |
| | Work Orders | ✅ (S30) | ❌ | Missing Dark |
| | Work Centers | ✅ (S11) | ❌ | Missing Dark |
| | Bill of Materials List | ✅ (S25) | ✅ (S28) | Consistent |
| | BOM Builder | ❌ | ❌ | Missing Both |
| **Admin/Ops** | Audit Logs | ✅ (S23) | ❌ | Missing Dark |
| | User Management | ❌ | ❌ | Missing Both |
| | Role Management | ❌ | ❌ | Missing Both |
| | Analytics Dashboard | ❌ | ❌ | Missing Both |
| | Reports Dashboard | ❌ | ❌ | Missing Both |

## 2. Consistency Analysis
- **Typography**: Current screens use varying title sizes. Need to enforce the new 48px/36px/24px scale.
- **Color**: Dark mode variants S3, S20, S26, S14, S28, S27, S8, S22 use #131316 surfaces. User requested transition to #0F172A (BG) and #111827 (Surface).
- **Navigation**: Mix of bottom tabs and side drawers. Standardizing on bottom tabs for core mobile navigation with a "More" menu for extended modules.
- **Components**: Status chips and buttons vary slightly in roundness. Standardizing on `ROUND_EIGHT`.

## 3. Immediate Action Plan
1. Establish the consolidated Design System.
2. Predict shared components (Global Bottom Nav, Header).
3. Generate the "Control Tower" Executive Dashboard (Dark & Light) with glassmorphism hero.
4. Fill critical gaps (Login, Dashboard, missing Dark variants).
