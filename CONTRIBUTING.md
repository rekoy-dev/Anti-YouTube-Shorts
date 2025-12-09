## 🤝 Contributing to Anti-YouTube-Shorts

Thank you for considering contributing! The success of this filter list relies on community vigilance and feedback. By reporting issues and suggesting improvements, you help keep the 'YouTube' focused.

Please take a moment to review the following guidelines before submitting a contribution.

### 🐛 Reporting Bugs (Broken Filters)

If you find that a YouTube Short, icon, or link is **not being blocked**, please open a **GitHub Issue**. This helps us track and fix broken filters efficiently.

When submitting a bug report, please include the following essential information:

1.  **Summary:** A brief, clear description of what is visible but should be hidden (e.g., "The Shorts tab on the left sidebar is still visible").
2.  **Platform/Setup:**
    * Which **browser** are you using (e.g., Chrome, Firefox, Edge)?
    * Which **uBlock extension** are you using (Origin, Lite, etc.)?
    * The **version** of the filter list you currently have installed (if known).
3.  **Specific URL:** The URL of the page where the element is visible (e.g., `https://www.youtube.com/feed/subscriptions`).
4.  **Screenshot/Video:** A clear image or short clip showing the element that is failing to be blocked.
5.  **Element Selector (Highly Recommended):** If you are comfortable inspecting HTML, please provide the CSS selector for the element that needs to be blocked.

### 💡 Suggesting Enhancements and Ideas

If you have a general idea for improving the project (e.g., better logic, new configuration options, compatibility with another extension or browser), please start a discussion in the **Ideas** category of our [Discussions Forum](link-to-your-discussions-tab).

### 🛠 Submitting Code Changes (Pull Requests)

We welcome contributions to the filter code itself! Since this is a list of filters, Pull Requests (PRs) primarily focus on updating the `filter.txt` file.

**Before creating a Pull Request:**

1.  **Start with an Issue or Discussion:** If your change is significant, please discuss it first via an Issue (for a fix) or Discussion (for a new feature) to ensure it aligns with the project goals.
2.  **Test Your Changes:** Verify that your proposed filter additions or modifications correctly block the intended element *without* breaking other parts of the YouTube UI.
3.  **Keep it Focused:** PRs should ideally focus on one specific fix or feature.

**How to submit a PR:**

1.  **Fork** the repository.
2.  Create a new branch for your changes (`git checkout -b fix/short-feed-block`).
3.  Apply your changes to the `filter.txt` file.
4.  Commit your changes clearly (`git commit -m 'FIX: Blocked new short feed row selector'`).
5.  Push to your branch and submit a Pull Request to the `main` branch.

I appreciate your effort and will review your contributions as quickly as possible!

Thank You,
Rekoy.
