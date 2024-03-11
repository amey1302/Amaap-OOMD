
# Election Results

### OOMD Design Election Result Display 
## class ElectionResultParser
 - ## State 
    - private inputFile 
    - private parsedData
 - ## Behavior
    - public parseResults()

## class Costituency
  - ## State
    - private name 
    - private List<Result> results

  - ## Behavior
     - addResult()
     -  determineWinner()

## enum Party
   - private final String partyName;
   - private final String partyCode;

 - ## Constructor 
   - Party(String partyName, String partyCode)
  
 - ## Behavior
   - public String getPartyName()
   - public String getPartyCode()

## class Result
  - ## State
    - private Party party 
    - private int votes 


## class ElectionResultDisplay
  - ## State
     - private List<Result> analyzedResults()

  - ## Behavior
     - public void displayResults()
	



