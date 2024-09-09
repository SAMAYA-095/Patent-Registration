# Patent-Registration
Patent office wants to launch the E-filing for Patents which will enable online filing of new applications for Patents. In patent application, applicant will provide the applicant details, inventor details, invention details for registration of patent.
Applicant will select the invention as proposed or completed. When invention is not complete, applicant will be selecting the invention as Provisional that will wait till 12 months. If invention is complete, applicant can submit the form.
Completed application will take 18 Months for publication of invention. Applicant can select the type of applicant category as start-up, small-entity or natural person on which different fees will be applicable.
Fees details as shown below:
Applicant Type	Fees
Start-up	4000
Small Entity	8000
Natural Person	1600
Application is published after 18 Months from filing date. If applicant do not wish to wait till the expiry of 18 Months from the date of filing then applicant can request for early
publication by paying the required fees. Once registration is done applicant will receive the mail. Note: Early publication request fees is 2500.
Once publication is completed applicant can request for patent examination. Patent examination will be done by the patent examiner. Patent examiner will check the inventions usability, novelty and patentability to approve once it is found meeting all requirements or may reject.
After approval from patent examiner patent certificate will be generated and email will be sent to customer with the Certificate of Patent. The validity of certificate is for 20 years.

Actors :	Applicant, Patent Examiner, Patent Officer

Mock up screens

![image](https://github.com/user-attachments/assets/33423d11-5061-4303-a9d3-938ca7906905)

![image](https://github.com/user-attachments/assets/9e57d131-77f2-4016-9b73-be9f01ebdd89)

![image](https://github.com/user-attachments/assets/4f70d370-5225-4bdf-ad6e-0612c75a4eb2)

![image](https://github.com/user-attachments/assets/59949b96-4d98-4ffb-8ce9-7b578b657167)

![image](https://github.com/user-attachments/assets/99b69ec3-a017-4b28-9d64-5f0eb62229a7)

![image](https://github.com/user-attachments/assets/c3883f6f-ba11-4308-bbf5-dd45b111349c)

![image](https://github.com/user-attachments/assets/7c5de6da-445b-4702-9ba4-b1fb9050498b)

![image](https://github.com/user-attachments/assets/f6b5bc41-8a51-4e4d-9ceb-f47fa754d3a8)

![image](https://github.com/user-attachments/assets/0474a03b-b81d-4baa-9476-39214f87fcf6)

Trigger	: Whenever the Patent filing is required.

Normal Flow

Case Life-cycle: File Patent

![image](https://github.com/user-attachments/assets/265cba5c-5f77-4733-a728-2ad57170a214)

Patent Registration : In this step the applicant need to enter Applicant Details , Inventor Details like First name, Last name, mobile number, email Id, address, nationality and Invention details like Type of application, Category of applicant, Patent status, Title of invention etc. After that applicant need to do Payment based on type of application and accept the declaration and Mail will be sent to Applicant.
Publication: It will take 18 months for the publication on invention from date of filing the patent. Patent officer need to review the applicant details, based on the details approve/reject the case and mail need to be sent to applicant. If applicant do not wish to wait till the expiry of 18 Months from the date of filing then optionally applicant can request for early publication by paying the required fees. Once registration is done applicant will receive the mail.
Examination Request: Applicant need to request for the examination by paying required fee and mail need to be sent to the applicant.
Patent Examination: Patent examination will be done by the patent examiner. Patent examiner will check the inventions patentability and decide to approve once it is found meeting all requirements or reject.
Grant Patent: After approval from patent examiner patent certificate will be generated and email will be sent to customer with the Certificate of Patent.

Alternate Flows
When Publication or Patent Examiner rejects the request, rejected status need to be
updated to the applicant along with the reason.

Exceptions	
Patent examiner rejects the patent as invention may not fulfil one or more criteria.

Frequency of Use : NA

Special Requirements	
If the application is provisional, claims cannot be made. Based on the applicant type, applicable fees need to be show.
Optionally applicant can request for early publication by paying the required fees. Date of birth must be a past date.
Date of filing must be the system date.

Future Requirements :	Applicant sign up

Assumptions	 : Applicant is already having operator ID.

Report

Report need to be generated as shown below:

1.Show all applicants details.

![image](https://github.com/user-attachments/assets/deba0807-e7bf-40bb-9fa2-03401aaaf850)

2.Show patents based on applicant category.

![image](https://github.com/user-attachments/assets/e7065faa-1082-4636-b3ab-4af1fd5024d3)

3.Show list of patents filed in current month.

![image](https://github.com/user-attachments/assets/f71b22ba-1ea9-4382-8558-6fd63dafaf52)














