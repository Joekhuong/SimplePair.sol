# SimplePair.sol
Remix - Deploy Contract On Base Network SimplePair.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract SimplePair {
    uint public x;
    uint public y;

    function set(uint _x, uint _y) public {
        x = _x;
        y = _y;
    }
}
