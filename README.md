
/ SPDX-License-Identifier: MIT
pragma solidity ^0.8.8;
// Import the AddressBook contract to interact with it
import "./AddressBook.sol";
11

// Contract for creating new instances of AddressBook
contract AddressBookFactory {

    string private salt = "value";
  // Function to deploy a new instance of AddressBook
    function deploy() external returns (AddressBook) {
        // Create a new instance of AddressBook
20
21
22
23
24
25
26
27
28
