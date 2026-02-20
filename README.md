# contract52.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

// Base network versioning smart contract
contract Contract51 {
    uint public version = 1;

    function upgrade() public {
        version++;
    }
}
