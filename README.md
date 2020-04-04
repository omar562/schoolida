# Schoolida

Schoolida is a famous school in Lebanon. Because of the current situation in Lebanon, Schoolida was obliged to send its staff and students to their homes. This did not only affect the teacher-student communication, but also the communication in between staff. Having said this, Schoolida is looking to implement an online system that manages:

## The staff

### Properties

Schoolida’s staff consists of:

* 1 principal
* 1 accountant
* 3 floor directors
* 20 teachers
* 2 counselors

All of them share the following information:

* first_name
* last_name
* phone_number
* address
* personal_email
* role (principal, accountant, floor director, teacher, counselor)
* schoolida_email (first_name.last_name@schoolida.com)
* base_salary (in LBP)
* bank_info
* bank_IBAN
  * bank_name
  * bank_branch

In addition to the above, each role can have special info:
teacher specific info:
-	employment_type (part-time or full-time) 
if part-time, the teacher will also have:
o	hourly_rate
o	monthly_hours
-	classes_taught (could be more than one)
counselor specific info:
-	office_days
-	office_hours (could be different for each day)

