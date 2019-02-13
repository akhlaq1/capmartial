To refresh database.
create database: python create_table.py

APIS:
POST http://127.0.0.1:5000/store_data
{
	"Date":"2013-09-10",
	"Inquiry_Call_In":1,
	"Inquiry_Walk_In":2,
	"Inquiry_Web":3,
	"Inquiry_Referral":4,
	"Inquiry_Other":5,
	"Total_Inquiries_Warm_Leads":6,
	"Appointments_Set":7,
	"Intro_1":8,
	"Intro_1_Attended_Showed":9,
	"Intro_2":10,
	"Intro_2_Attended_Showed":11,
	"Enrollment_Conferences":12,
	"Renewal_Upgrade_Conferences":13,
	"no_of_Cancellations":14,
	"Dragon":15,
	"Basic":16,
	"Mastery":17,
	"Adults":18,
	"Total":19,
	"no_of_Enrollments":20,
	"Student_Count_1st_Day":21,
	"Student_Count_2nd_Day":22,
	"no_of_Upgrades_Renewals":23,
	"Tuition":24.1,
	"Compression":25.2,
	"Retail":26.3,
	"Special_Event":27.4,
	"Promotion_Fee":27.5,
	"Down_Payments_Daily":28.6,
	"Cancellation_Fees":29.7,
	"Other_Revenue":30.8,
	"Refunds":31.9,
	"Total_Gross_Revenue":32.1,
	"Net_Billing_Change":33.2,
	"Down_Payments":34.3,
	"Monthly_Payment_Total":35.4,
	"Down_Payments_Total":36.5,
	"Monthly_Payment_Increase":37.6,
	"Cancellation_Fee_Collected":38.7,
	"Reduction_in_Monthly_Payment":39.8,
	"no_upgrades_renewals_total":40,
	"Down_payments_total_total":41.1,
	"Monthly_Payments_Increase_total":42.2 
} 

GET http://127.0.0.1:5000/records_by_date/2013-09-10/2013-09-15