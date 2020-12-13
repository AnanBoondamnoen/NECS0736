## Test Case : V1.2 Authentication Architectural Requirements

| Test Case  | Preconditions | Inputs | Actions | Expect results | Postconditions |
| ------- | ------  | ------  | ------  | ------  | ------  |
| Attacker can reset an account by calling a call center and answering correct commonly known questions  | Complete Calling  | Identity Answer | Calling | Can reset password | Attack can steal victim's account |
| Attacker can reset an account by calling a call center and answering wrong commonly known questions  | Complete Calling  | Identity Answer | Calling | Can't reset password | Attack can't steal victim's account |

### Members
- Anan Boondamnoen
- Soontorn Janphuk