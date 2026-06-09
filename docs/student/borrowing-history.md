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
                <a href="../../README.md">Homepage</a>                   
                <p><strong>1. Authentication & Identity</strong></p>
                <ul style="list-style-type: none; padding-left: 0; font-size: 0.9em;">
                    <li style="padding-left: 15px"> <a href="../auth/authentication-sign-up.md"> Login with Google (FR 1.0) </a></li>
                </ul>
                <p><strong>2. Student Viewer Hub</strong></p>
                <ul style="list-style-type: none; padding-left: 0; font-size: 0.9em;">
                    <li style="padding-left: 15px"><a href="dashboard.md">Dashboard (FR 1.0)</a></li>
                    <li style="padding-left: 15px"><a href="reserve-book.md">Reserve Book (FR 2.0)</a></li>
                    <li style="padding-left: 15px"><a href="reservation-notifier.md">Reservation Notifier (FR 2.1)</a></li>
                    <li style="padding-left: 15px"><a href="book-search.md">Book Search (FR 3.0)</a></li>
                    <li style="padding-left: 15px"><a href="availability.md">Real-Time Availability (FR 4.0)</a></li>
                    <li style="padding-left: 15px"><a href="borrowing-history.md">Borrowing History (FR 5.0)</a></li>
                    <li style="padding-left: 15px"><a href="book-categories.md">Book Categories (FR 6.0)</a></li>
                </ul>
                <p><strong>3. Librarian Management Portal</strong></p>
                <ul style="list-style-type: none; padding-left: 0; font-size: 0.9em;">
                    <li style="padding-left: 15px"><a href="../librarian/dashboard.md">Librarian Dashboard (FR 7.0)</a></li>
                    <li style="padding-left: 15px"><a href="../librarian/approve-checkout.md">Approve Checkout (FR 7.0)</a></li>
                    <li style="padding-left: 15px"><a href="../librarian/process-return.md">Process Return (FR 7.0)</a></li>
                    <li style="padding-left: 15px"><a href="../librarian/book-record-manager.md">Book Record Manager (FR 7.0)</a></li>
                    <li style="padding-left: 15px"><a href="../librarian/overdue-notifier.md">Overdue Notifier (FR 8.0)</a></li>
                </ul>
                <p><strong>4. Shared</strong></p>
                <ul style="list-style-type: none; padding-left: 0; font-size: 0.9em;">
                    <li style="padding-left: 15px"><a href="../shared/account-settings.md">Account Settings (FR 1.0)</a></li>
                    <li style="padding-left: 15px"><a href="../shared/book-detail.md">Book Detail (FR 3.0 / 4.0)</a></li>
                    <li style="padding-left: 15px"><a href="../shared/notification-center.md">Notification Center (FR 2.1 / 8.0)</a></li>
                </ul>
            </td>
            <td valign="top" style="border: 1px solid #e0e0e0; padding: 20px;">
                <div style="margin-bottom: 15px; font-size: 0.85em; color: #666;">
                    <a href="." style="text-decoration: none;">Student Viewer Hub</a> &gt; 
                    <a href="borrowing-history.md" style="color: #ac9e9e; font-weight: bold; text-decoration: none;">Borrowing History</a>
                </div>           
                <div style="margin: 20px 0; text-align: center; border: 1px dashed #ccc; padding: 15px;">
                    <img src="../../assets/borrowing_history.png" alt="Borrowing History Screenshot" style="max-width: 100%;">
                </div>
                <h2 style="margin-top: 0;">Borrowing History (FR 5.0)</h2>
                <p>The Borrowing History feature allows students to view a complete record of all books they have borrowed or reserved in the past. This includes currently active borrowings, past borrowings, and reservation history. Students can track their reading activity and revisit books they have previously checked out.</p>
                <p>The history includes details such as book title, author, borrowing date, return date, and status (returned, overdue, or lost). This feature helps students keep track of their library usage and identify books they may want to borrow again in the future.</p>
                <h3>Use Case Scenario</h3>
                <table border="1" width="100%" cellpadding="8" cellspacing="0" style="border-collapse: collapse; font-size: 0.9em; border: 1px solid #ddd;">
                    <tr>
                        <th width="20%" align="left">Actor(s)</th>
                        <td>Student</d>
                    </tr>
                    <tr>
                        <th align="left">Goal</th>
                        <td>To view past and current borrowing records and track library activity.</d>
                    </tr>
                    <tr>
                        <th align="left">Preconditions</th>
                        <td>1. Student is logged into the system.<br>2. Student has borrowed or reserved books in the past.</d>
                    </tr>
                    <tr>
                        <th align="left">Main Scenario</th>
                        <td>1. Student navigates to the Borrowing History page.<br>2. System displays a list of all past and current borrowings.<br>3. Student can filter history by status (active, returned, overdue).<br>4. Student selects a record to view detailed borrowing information.<br>5. System shows book details, borrowing dates, and return status.</d>
                    </tr>
                    <tr>
                        <th align="left">Outcome</th>
                        <td>Student can review their library activity and identify books they have previously borrowed.</d>
                    </tr>
                </table>
            </d>
        </tr>
        <tr>
            <td colspan="2" align="center" style="padding-top: 30px; font-size: 0.8em; color: #999;">
                <hr style="border: 0; border-top: 1px solid #eee; margin-bottom: 10px;">
                © 2026 DigitalWare | OnTrack VSU SSC
            </d>
        </tr>
    </table>
</div>