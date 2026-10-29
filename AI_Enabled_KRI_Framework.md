# AI-Enabled KRI Collection and Analysis Framework

## 1. Automated Monthly KRI Request to HO Units

- AI reads a master KRI inventory.
- On a predefined date (e.g., 1st day of each Nepali month), emails are automatically sent to each HO Department.
- Each department receives only its relevant KRIs and reporting template.

---

## 2. Intelligent Reminder Engine

- Reminder 1: 10th day.
- Reminder 2: 13th day.
- Final Reminder: 15th day.
- Escalation to Department Head after the due date.

---

## 3. Structured Collection

Instead of free-text emails:

- Web Form / Microsoft Forms / SharePoint Form.
- Department-specific questionnaire.
- Mandatory fields and attachments.
- Automated submission acknowledgement.

---

## 4. AI-Based Data Extraction

If departments continue sending Excel files or email responses:

- AI reads the email and attachments.
- Extracts KRI values automatically.
- Maps values to the corresponding KRI fields.
- Updates the central KRI database.

---

## 5. Automatic Threshold Assessment

The system compares reported values against thresholds defined in the Bank's Process Note.

### Example

- KRI ≤ Limit → **Green**
- KRI Approaching Limit → **Amber**
- KRI Exceeding Limit → **Red**

No manual review is required.

---

## 6. RAG Dashboard

AI generates:

- Department-wise RAG status.
- KRI-wise RAG status.
- Trend analysis over the last 6/12 months.
- Top 10 Red KRIs.
- Emerging Risks.

---

## 7. Automated Commentary

Instead of manually preparing reports, AI generates observations such as:

> IT downtime exceeded the Red threshold in the ICT Department for the second consecutive month.

> Customer complaint levels increased by 20% compared to the previous month.

---

## 8. Escalation Workflow

For Red KRIs:

- Notify Department Head.
- Request Root Cause Analysis (RCA).
- Request Corrective Action Plan (CAP).
- Track closure status.

---

## 9. Integration with Existing ORMSS

### Long-Term Approach

- Branch KRIs continue to be submitted through ORMSS.
- HO KRIs are collected through an AI-enabled portal.
- A single enterprise dashboard consolidates data from both sources.

---

## 10. Management Dashboard

The dashboard provides:

- Submission Compliance (%)
- Pending Departments
- Branch vs HO Comparison
- RAG Heat Map
- Trend Charts
- Monthly Operational Risk Score

---

# End-State Vision

```text
AI Sends KRI Request
          ↓
Department Submits Data
          ↓
AI Validates & Captures Data
          ↓
Threshold Assessment
          ↓
Red / Amber / Green Classification
          ↓
Dashboard Refresh
          ↓
AI Generates Commentary
          ↓
Automatic Escalation for Red KRIs
```

---

# Implementation Roadmap

## Phase 1: Process Automation

- Automated KRI request emails.
- Automated reminder and escalation workflow.
- Centralized KRI collection repository.

## Phase 2: Risk Analytics

- Automated threshold evaluation.
- Red/Amber/Green classification.
- Dashboard and trend reporting.

## Phase 3: AI Enablement

- AI extraction of KRI data from emails and attachments.
- AI-generated risk insights and commentary.
- Automated exception reporting.

## Phase 4: Enterprise Integration

- Integration with ORMSS.
- Unified Branch and HO KRI dashboard.
- Enterprise-wide Operational Risk reporting and analytics.

---

# Expected Benefits

- Reduced manual follow-up effort.
- Improved submission timeliness.
- Better data quality and consistency.
- Faster KRI analysis.
- Automated RAG classification.
- Real-time risk visibility.
- Enhanced management reporting.
- Stronger operational risk governance.
