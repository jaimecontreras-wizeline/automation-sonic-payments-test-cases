Front-end automation project for payments (positive and negative test cases). This project automates payment workflow.

Test cases automated:

- Payment with invalid CVV code.
- Payment with expired card.
- Payment successful.
- Payment with redirect card.

Before you run this project, please make sure that project fr-monetization-test-web is running.

To run this project on your own machine, follow the steps below:

1. Clone this project:
   git clone https://github.com/jaimecontreras-wizeline/automation-sonic-payments-test-cases.git

2. Download all dependencies:
   npm install
3. Add this ENV vars
   export TESTRAIL_ENABLE=true
   export TESTRAIL_HOST=https://discovery.testrail.io/
   export TESTRAIL_USER=youruser@discovery.com
   export TESTRAIL_PASS=*****
   export PROJECT_NAME="Discovery Payments Simulator"
   export TESTRAIL_ENABLE=true


4. Run all test cases with the following command:
   npm run payments
