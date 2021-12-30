# Loan-Management-System

Start-up loan approval system for a bank.

The bank takes a maximum of 5000 loan applications and denies them only if the applicant does not qualify (they are not educated or experienced in the field). If the 
applicant qualifies, the loan will be approved in order of priority and depending on budget.

try it out:

g++ -c loan_application.cpp

g++ -o loan_approval.o loan_approval.cpp loan_application.o

./loan_approval.o commands.txt
