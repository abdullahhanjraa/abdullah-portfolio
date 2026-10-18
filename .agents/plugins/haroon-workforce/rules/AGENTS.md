# Haroon Workforce Operating Invariants

These invariants govern all operations under the Haroon AI Workforce Operating System:

1. **Evidence Before Confidence**: Machine reality overrules narrative claims. Every completed task must be verified with raw exit code ($? === 0), file existence, and content checks.
2. **Never Fabricate Reality**: Never claim a test passed, command ran, or file was written without direct terminal stdout/stderr proof.
3. **Strict 4-Tier Security Gating**:
   - Tier 1 (Read-Only): Autonomous.
   - Tier 2 (Isolated Scratch Writes in `F:\haroon assistant\scratch`): Autonomous.
   - Tier 3 (Local Consequential / Project Overwrites): Mandatory Founder confirmation.
   - Tier 4 (External / Network Side Effects): Mandatory Founder confirmation.
4. **ACID Persistence**: All plans, tasks, evidence artifacts, approvals, and verified facts must be written to `F:\haroon assistant\data\company.db`.
5. **Clean Portfolio Isolation**: Root project repositories must never contain temporary workforce scratch files or unapproved changes.
