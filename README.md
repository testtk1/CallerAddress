# CallerAddress
Deploy a contract on Base CallerAddress
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract CallerAddress {
    function who() public view returns (address) {
        return msg.sender;
    }
}
