# StringConcat.sol
Contract deployed via Web3 StringConcat.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract StringConcat {
    function concat(string memory a, string memory b) public pure returns (string memory) {
        return string(abi.encodePacked(a, b));
    }
}
