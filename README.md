Install Required Libraries:
Ensure you have json (which is part of Python's standard library) and uuid installed for unique ticket generation:
pip install uuid
create_ticket(): Generates a unique ticket ID, records the customer's name, issue, and timestamps, then stores this information in an in-memory database (a dictionary).
view_ticket(): Allows the user to retrieve and view details of a specific ticket using its ID.
update_ticket_status(): Enables the status of a ticket (e.g., "Open", "In Progress", "Closed") to be updated, along with the last updated timestamp.
list_all_tickets(): Lists all tickets stored in the system.
main(): Provides a command-line interface where users can create tickets, view ticket details, update ticket statuses, and list all tickets.
