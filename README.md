# Constructor
Only constructor for ethereum smart contract

pragma solidity ^0.7.5;

contract king
{
    string message;

    constructor(string memory _message)
    {
        message = _message;
    }

    function get() public view returns(string memory)
    {
        return message;
    } 
}
