# add-contract-Substitute
  contract Substitute is ITeacher {
    function hourlyRate() external pure override returns (uint) {
        return 20;
       }
