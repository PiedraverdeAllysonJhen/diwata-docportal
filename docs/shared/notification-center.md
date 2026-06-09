<div>
    <table width="100%" cellpadding="10" cellspacing="0" style="font-family: Arial, sans-serif; border-collapse: collapse;">
        <tr>
            <td colspan="2" style="padding-bottom: 20px;">
                <h1 style="margin: 0;">DigitalWare Library System</h1>
                <p style="font-weight: lighter; margin: 0;">Target: DW010.001</p>
            </td>
        </tr>
        <tr>
            <td width="25%" valign="top" style="border: 1px solid #e0e0e0; border-right: none;">
                <h2 style="margin-top: 0;">Site Map</h2>
                <a href="README.md">Homepage</a>                   
                <p><strong>1. Authentication & Identity</strong></p>
                <ul style="list-style-type: none; padding-left: 0; font-size: 0.9em;">
                    <li style="padding-left: 15px"> <a href="docs/auth/authentication-sign-up.md"> Login with Google (FR 1.0) </a></li>
                </ul>
                <p><strong>2. Student Viewer Hub</strong></p>
                <ul style="list-style-type: none; padding-left: 0; font-size: 0.9em;">
                    <li style="padding-left: 15px"><a href="docs/student/dashboard.md">Dashboard (FR 1.0)</a></li>
                    <li style="padding-left: 15px"><a href="docs/student/reserve-book.md">Reserve Book (FR 2.0)</a></li>
                    <li style="padding-left: 15px"><a href="docs/student/reservation-notifier.md">Reservation Notifier (FR 2.1)</a></li>
                    <li style="padding-left: 15px"><a href="docs/student/book-search.md">Book Search (FR 3.0)</a></li>
                    <li style="padding-left: 15px"><a href="docs/student/availability.md">Real-Time Availability (FR 4.0)</a></li>
                    <li style="padding-left: 15px"><a href="docs/student/borrowing-history.md">Borrowing History (FR 5.0)</a></li>
                    <li style="padding-left: 15px"><a href="docs/student/book-categories.md">Book Categories (FR 6.0)</a></li>
                </ul>
                <p><strong>3. Librarian Management Portal</strong></p>
                <ul style="list-style-type: none; padding-left: 0; font-size: 0.9em;">
                    <li style="padding-left: 15px"><a href="docs/librarian/dashboard.md">Librarian Dashboard (FR 7.0)</a></li>
                    <li style="padding-left: 15px"><a href="docs/librarian/approve-checkout.md">Approve Checkout (FR 7.0)</a></li>
                    <li style="padding-left: 15px"><a href="docs/librarian/process-return.md">Process Return (FR 7.0)</a></li>
                    <li style="padding-left: 15px"><a href="docs/librarian/book-record-manager.md">Book Record Manager (FR 7.0)</a></li>
                    <li style="padding-left: 15px"><a href="docs/librarian/overdue-notifier.md">Overdue Notifier (FR 8.0)</a></li>
                </ul>
                <p><strong>4. Shared</strong></p>
                <ul style="list-style-type: none; padding-left: 0; font-size: 0.9em;">
                    <li style="padding-left: 15px"><a href="docs/shared/account-settings.md">Account Settings (FR 1.0)</a></li>
                    <li style="padding-left: 15px"><a href="docs/shared/book-detail.md">Book Detail (FR 3.0 / 4.0)</a></li>
                    <li style="padding-left: 15px"><a href="docs/shared/notification-center.md">Notification Center (FR 2.1 / 8.0)</a></li>
                </ul>
            </td>
            <td valign="top" style="border: 1px solid #e0e0e0; padding: 20px;">
                <div style="margin-bottom: 15px; font-size: 0.85em; color: #666;">
                    <a href="docs/shared/" style="text-decoration: none;">Shared</a> &gt; 
                    <a href="docs/shared/notification-center.md" style="color: #ac9e9e; font-weight: bold; text-decoration: none;">Notification Center</a>
                </div>           
                <div style="margin: 20px 0; text-align: center; border: 1px dashed #ccc; padding: 15px;">
                    <img src="../../assets/notification_center.png" alt="Notification Center Screenshot" style="max-width: 100%;">
                </div>
                <h2 style="margin-top: 0;">Notification Center (FR 2.1 / 8.0)</h2>
                <p>The Notification Center is a shared component that aggregates all system notifications for both students and librarians. It provides a centralized view of reservation confirmations, status updates, overdue alerts, and other important system messages. Users can access their notification history and manage notification preferences from this interface.</p>
                <p>Notifications are displayed in real-time with read/unread status indicators. Users can mark notifications as read, archive them, or click through to view related content. The Notification Center integrates with the Reservation Notifier (FR 2.1) for students and Overdue Notifier (FR 8.0) for librarians.</p>
                <h3>Use Case Scenario</h3>
                <table border="1" width="100%" cellpadding="8" cellspacing="0" style="border-collapse: collapse; font-size: 0.9em; border: 1px solid #ddd;">
                    <tr>
                        <th width="20%" align="left">Actor(s)</th>
                        <td>Student, Librarian</d>
                    </tr>
                    <tr>
                        <th align="left">Goal</th>
                        <td>To view and manage all system notifications in one centralized location.</d>
                    </tr>
                    <tr>
                        <th align="left">Preconditions</th>
                        <td>1. User is logged into the system.<br>2. User has received notifications from system features.</d>
                    </tr>
                    <tr>
                        <th align="left">Main Scenario</th>
                        <td>1. User clicks the Notification Center icon or navigates to the page.<br>2. System displays a list of all notifications with read/unread status.<br>3. User clicks on a notification to view details.<br>4. System redirects to the relevant page (reservation, book detail, etc.).<br>5. User marks notifications as read or archives them.<br>6. System updates notification status in real-time.</d>
                    </tr>
                    <tr>
                        <th align="left">Outcome</th>
                        <td>User can efficiently manage and respond to all system notifications from a single interface.</d>
                    </tr>
                </table>
            </d>
        </tr>
        <tr>
            <td colspan="2" align="center" style="padding-top: 30px; font-size: 0.8em; color: #999;">
                <hr style="border: 0; border-top: 1px solid #eee; margin-bottom: 10px;">
                © 2026 BookItStudent | VSU Library System
            </d>
        </tr>
    </table>
</div>