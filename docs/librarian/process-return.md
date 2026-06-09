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
                </ul>
                <p><strong>4. Shared</strong></p>
                <ul style="list-style-type: none; padding-left: 0; font-size: 0.9em;">
                    <li style="padding-left: 15px"><a href="../shared/book-detail.md">Book Detail (FR 3.0 / 4.0)</a></li>
                    <li style="padding-left: 15px"><a href="../shared/notification-center.md">Notification Center (FR 2.1 / 8.0)</a></li>
                </ul>
            </td>
            <td valign="top" style="border: 1px solid #e0e0e0; padding: 20px;">
                <div style="margin-bottom: 15px; font-size: 0.85em; color: #666;">
                    <a href="." style="text-decoration: none;">Librarian Management Portal</a> &gt; 
                    <a href="process-return.md" style="color: #ac9e9e; font-weight: bold; text-decoration: none;">Process Return</a>
                </div>           
                <div style="margin: 20px 0; text-align: center; border: 1px dashed #ccc; padding: 15px;">
                    <img src="../../assets/return_process.png" alt="Process Return Screenshot" style="max-width: 100%;">
                </div>
                <h2 style="margin-top: 0;">Process Return (FR 7.0)</h2>
                <p>The Process Return feature allows librarians to record the return of borrowed books into the system. When a student returns a book, the librarian uses this feature to update the book's status from "Checked Out" to "Available" and clear the borrowing record from the student's account.</p>
                <p>This feature calculates any overdue fines based on the return date versus the due date. If fines are applicable, the system records the amount and notifies the student. The processed return is immediately reflected in the book's availability status and the student's borrowing history.</p>
                <h3>Use Case Scenario</h3>
                <table border="1" width="100%" cellpadding="8" cellspacing="0" style="border-collapse: collapse; font-size: 0.9em; border: 1px solid #ddd;">
                    <tr>
                        <th width="20%" align="left">Actor(s)</th>
                        <td>Librarian</d>
                    </tr>
                    <tr>
                        <th align="left">Goal</th>
                        <td>To record a returned book, update its status, and calculate any applicable overdue fines.</d>
                    </tr>
                    <tr>
                        <th align="left">Preconditions</th>
                        <td>1. Librarian is logged into the system.<br>2. The book was previously checked out by a student.<br>3. The student returns the physical book to the library.</d>
                    </tr>
                    <tr>
                        <th align="left">Main Scenario</th>
                        <td>1. Librarian searches for the student or scans the book barcode.<br>2. System displays the active borrowings for the student or book.<br>3. Librarian selects the borrowing record to process return.<br>4. System calculates overdue fines if return date is past due date.<br>5. Librarian confirms the return.<br>6. System updates book status to "Available."<br>7. System removes the borrowing from the student's active list.<br>8. System sends a return confirmation notification to the student.</d>
                    </tr>
                    <tr>
                        <th align="left">Outcome</th>
                        <td>Book return is recorded. Book status is updated. Any overdue fines are calculated and recorded. Student receives return confirmation.</d>
                    </tr>
                </table>
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