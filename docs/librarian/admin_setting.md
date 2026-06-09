<div>
    <table width="100%" cellpadding="10" cellspacing="0" style="font-family: Arial, sans-serif; border-collapse: collapse;">
        <tr>
            <td colspan="2" style="padding-bottom: 20px;">
                <h1 style="margin: 0;">DIWATA</h1>
                <p style="font-weight: lighter; margin: 0;">Target: `DW010.001`</p>
            </td>
        </tr>
        <tr>
            <td width="25%" valign="top" style="border: 1px solid #e0e0e0; border-right: none;">
                <h2 style="margin-top: 0;">Site Map</h2>
                <a href="../../README.md">Homepage</a>                   
                <p><strong>1. Authentication & Identity</strong></p>
                <ul style="list-style-type: none; padding-left: 0; font-size: 0.9em;">
                    <li style="padding-left: 15px"> <a href="../auth/authentication-sign-up.md"> Login with Google (FR 1.0) </a></li>
                </ul>
                <p><strong>2. Student Viewer Hub</strong></p>
                <ul style="list-style-type: none; padding-left: 0; font-size: 0.9em;">
                    <li style="padding-left: 15px"><a href="../student/dashboard.md">Dashboard (FR 1.0)</a></li>
                    <li style="padding-left: 15px"><a href="../student/reserve-book.md">Reserve Book (FR 2.0)</a></li>
                    <li style="padding-left: 15px"><a href="../student/reservation-notifier.md">Reservation Notifier (FR 2.1)</a></li>
                    <li style="padding-left: 15px"><a href="../student/book-search.md">Book Search (FR 3.0)</a></li>
                    <li style="padding-left: 15px"><a href="../student/availability.md">Real-Time Availability (FR 4.0)</a></li>
                    <li style="padding-left: 15px"><a href="../student/borrowing-history.md">Borrowing History (FR 5.0)</a></li>
                    <li style="padding-left: 15px"><a href="../student/book-categories.md">Book Categories (FR 6.0)</a></li>
                    <li style="padding-left: 15px"><a href="../student/account-settings.md">Account Settings (FR 1.0)</a></li>
                </ul>
                <p><strong>3. Librarian Management Portal</strong></p>
                <ul style="list-style-type: none; padding-left: 0; font-size: 0.9em;">
                    <li style="padding-left: 15px"><a href="dashboard.md">Librarian Dashboard (FR 7.0)</a></li>
                    <li style="padding-left: 15px"><a href="approve-checkout.md">Approve Checkout (FR 7.0)</a></li>
                    <li style="padding-left: 15px"><a href="process-return.md">Process Return (FR 7.0)</a></li>
                    <li style="padding-left: 15px"><a href="book-record-manager.md">Book Record Manager (FR 7.0)</a></li>
                    <li style="padding-left: 15px"><a href="overdue-notifier.md">Overdue Notifier (FR 8.0)</a></li>
                    <li style="padding-left: 15px"><a href="admin-settings.md">Admin Settings</a></li>
                </ul>
                <p><strong>4. Shared</strong></p>
                <ul style="list-style-type: none; padding-left: 0; font-size: 0.9em;">
                    <li style="padding-left: 15px"><a href="../shared/book-detail.md">Book Detail (FR 3.0 / 4.0)</a></li>
                    <li style="padding-left: 15px"><a href="../shared/notification-center.md">Notification Center (FR 2.1 / 8.0)</a></li>
                </ul>
            </d>
            <td valign="top" style="border: 1px solid #e0e0e0; padding: 20px;">
                <div style="margin-bottom: 15px; font-size: 0.85em; color: #666;">
                    <a href="." style="text-decoration: none;">Librarian Management Portal</a> &gt; 
                    <a href="admin-settings.md" style="color: #ac9e9e; font-weight: bold; text-decoration: none;">Admin Settings</a>
                </div>           
                <div style="margin: 20px 0; text-align: center; border: 1px dashed #ccc; padding: 15px;">
                    <img src="../../assets/admin_settings.png" alt="Admin Settings Screenshot" style="max-width: 100%;">
                </div>
                <h2 style="margin-top: 0;">Admin Settings</h2>
                <p>The Admin Settings feature allows librarians and administrators to configure global system preferences, library operation rules, and circulation defaults. This includes setting pickup windows, loan durations, fine rates, and notification preferences for the entire library system.</p>
                <p>These settings apply to all users and library operations, ensuring consistent policies across the institution.</p>
                <h3>Workspace Controls - Library Admin Preferences</h3>
                <h4>📦 Pickup Window</h4>
                <p>Sets the time limit for students to pick up their reserved books before the reservation automatically expires. If a student does not claim the book within this window, the reservation is cancelled and the book becomes available for other students.</p>
                <p><strong>Default setting:</strong> 48 hours before auto-expiration</p>
                <h4>⏱️ Loan Duration</h4>
                <p>Defines the standard borrowing period for books checked out by students. The system automatically calculates the due date based on this setting and sends reminders as the due date approaches.</p>
                <p><strong>Default setting:</strong> 7 days before due date</p>
                <h4>💰 Fine Rate</h4>
                <p>Sets the penalty amount charged per day when a student returns a book after the due date. The system automatically calculates fines based on this rate and the number of overdue days.</p>
                <p><strong>Default setting:</strong> 50 pesos per overdue day</p>
                <h3>Use Case Scenario</h3>
                <table border="1" width="100%" cellpadding="8" cellspacing="0" style="border-collapse: collapse; font-size: 0.9em; border: 1px solid #ddd;">
                    <tr>
                        <th width="20%" align="left">Actor(s)</th>
                        <td>Librarian / Administrator</d>
                    </tr>
                    <tr>
                        <th align="left">Goal</th>
                        <td>To configure global library policies including pickup window, loan duration, and fine rates.</d>
                    </tr>
                    <tr>
                        <th align="left">Preconditions</th>
                        <td>1. User is logged in with Administrator privileges.<br>2. User has permission to modify system settings.</d>
                    </tr>
                    <tr>
                        <th align="left">Main Scenario</th>
                        <td>1. Administrator navigates to Admin Settings page.<br>2. System displays current configuration values.<br>3. Administrator modifies Pickup Window, Loan Duration, or Fine Rate.<br>4. System validates the input values.<br>5. Administrator saves the changes.<br>6. System applies new settings to all future library transactions.<br>7. System confirms the settings have been updated.</d>
                    </tr>
                    <tr>
                        <th align="left">Alternative Flow</th>
                        <td>If invalid values are entered (e.g., negative numbers), the system displays an error message and reverts to previous valid settings.</d>
                    </tr>
                    <tr>
                        <th align="left">Outcome</th>
                        <td>Global library policies are updated. All future reservations, checkouts, and fine calculations use the new settings.</d>
                    </tr>
                </table>
                <h3>Quick Actions</h3>
                <ul>
                    <li>📋 Export Reports - Generate system configuration reports</li>
                </ul>
            </d>
        </tr>
        <tr>
            <td colspan="2" align="center" style="padding-top: 30px; font-size: 0.8em; color: #999;">
                <hr style="border: 0; border-top: 1px solid #eee; margin-bottom: 10px;">
                   © 2026 Enera  | BookItStudent
            </d>
        </tr>
    </table>
</div>