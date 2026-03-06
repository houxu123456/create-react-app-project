
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

    uint24 private salary;
    uint16 private shares;

    constructor() {
        name = "Pat";
        idNumber = 112358132134;
        salary = 50000;
        shares = 1000;
    }

    function grantShares(uint16 _newShares) external {
        require(_newShares <= 5000, "Too many shares");
        shares += _newShares;
    }

    function checkForPacking(uint _slot) external view returns (uint result) {
        assembly {
            result := sload(_slot)
        }
    }

    function viewShares() external view returns (uint16) {
        return shares;
    }

    function viewSalary() external view re











