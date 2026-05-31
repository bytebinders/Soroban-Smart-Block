#121 Implement a Visual Storage Layout Schema Mapper
Repo Avatar
Soroban-Smart-Block-Explorer/Soroban-Smart-Block
Description: Create an educational diagram tool that visualizes how a contract organizes and distributes data across its internal state storage maps.

Technical Considerations: Parse the contract's type definitions to display a visual breakdown of active storage keys, data types, and value allocations.

Acceptance Criteria: The interface displays an interactive chart mapping out the contract's state organization, making it easy for developers to inspect storage layouts.

#122 Build an Interactive XDR-to-JSON Conversion Workbench
Repo Avatar
Soroban-Smart-Block-Explorer/Soroban-Smart-Block
Description: Create a utility dashboard where developers can paste raw base64 XDR strings to instantly view a decoded, formatted JSON representation of the data.

Technical Considerations: Use fast client-side decoding libraries to parse the input data safely within the browser sandbox, handling any invalid inputs gracefully.

Acceptance Criteria: Pasting an XDR string instantly displays an organized, color-coded JSON data tree, complete with quick options to copy specific fields.