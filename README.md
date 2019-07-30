## Backend Developer at Give

### Objective
Create a disbursement report from a list of donations in CSV.

### Tasks
- The app should allow user to select the base currency and upload a CSV file containing donation data.
- The app should parse the CSV and validate the format for each row as [Date,Order Id,Nonprofit,Donation Currency,Donation Amount,Fee]
- The app should convert all donation amounts into the user-selected base currency using any currency exchange API such as https://openexchangerates.org/ or https://exchangeratesapi.io/
- The app should group the donations according to nonprofit and return a new CSV file which contains aggregated information for each nonprofit. [Nonprofit, Total amount, Total Fee, Number of Donations]
- A [sample CSV file](sample.csv) is provided in the repository for testing

### Deliverables
- Create a fork of this repository
- Use simple html to provide the option to upload CSV. Frontend doesn't need to be fancy
- Include instructions on how to set it up and run in the README.md
- Add your resume and other profile / project links
- Submit a pull request (PR)
