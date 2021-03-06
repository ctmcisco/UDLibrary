# UDLibrary

UDLibrary is a book collection dashboard built on Universal Dashboard. My wife, the avid book collector has _hundreds_ of books.
This project aims to give her a mobile interface to be able to catalog, and loan out books to friend/family. Obviously, there are no strict rules for the loaning of books,
but the feature gives her the ability to remember who has what if something is requested.

Being able to search her library will be helpful as well if she's at a store and wonders "Do I already have this"?

Requirements:

- Universal Dashboard Community Edition (`Install-Module UniversalDashboard.Community -Force`)
- SQL Server Express (`choco install sql-server-express -y`)

Using this dashboard

1. Clone this library: `git clone https://github.com/steviecoaster/UDLibrary.git`
2. Change into cloned directory: `Set-Location .\UDLibrary` (_Adjust path as necessary_)
3. Start the dashboard: `. .\src\dashboard.ps1`

To Stop the dashboard run `Get-UDDashboard | Stop-UDDashboard`