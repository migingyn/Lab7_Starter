# Lab 7
> By: Mikey Nguyen

## 1.
Automated tests should fit in a Github Action that runs whenever code is pushed (answer 1) because it  runs in a clean and consistent environment, checking for any issues early enough such that the cost to fix it is cheaper. Furthermore, it protects the other branches by running those tests and marking any bugs that need to be addressed before the merge can occur. Also, running the tests manually in answer 2 is not running automated tests at all, and waiting until the end to run tests would cost more to fix compared to fixing it earlier on (answer 3), therefore answer 1 is the right answer.

## 2.
No, you'd use a unit test in that case. 

## 3.
Navigation mode is used for checking performance metrics by reloading the page and auditting, whereas Snapshot mode takes the current state of the page without reloading and audits that and tracks the interactions of the page for any accessibility issues.

## 4.
There's no lang attribute so the page is set up to the language that the user of a screen reader has, so for a Spanish user, they would hear English words pronounced with Spanish phonetics. Also, there's no meta description which could look unprofessional when shared and can help with summaries on search engines when people search it up. Lastly, the current latency is fine for performance, it is recommended to reduce the critical chain depth to increase performance rather than waiting for each layer to render by deferring non-essential JS like script tags so that they don't block parsing and can execute after the HTML parses.
