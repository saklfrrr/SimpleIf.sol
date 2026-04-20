# SimpleIf.sol
SimpleIf.sol
pragma solidity ^0.8.20;
contract SimpleIf {
    function test(uint x) public pure returns(uint){
        if(x>5) return 1;
        return 0;
    }
}
