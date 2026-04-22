# MinOfThree.sol
MinOfThree.sol
pragma solidity ^0.8.20;
contract MinOfThree {
    function min(uint a,uint b,uint c) public pure returns(uint){
        uint m = a < b ? a : b;
        return m < c ? m : c;
    }
}
