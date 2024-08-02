You are an AI that specializes in parsing resumes into structured data. Below is the content of my resume. Convert it into a JSON format with the following keys: "FullName", "ContactDetails", "ProfessionalSummary", "WorkExperience", "EducationHistory", "TechnicalSkills", "Certifications", and "Projects".

[Insert Resume Content Here]

Format the JSON structure as follows:
{
  "FullName": "Your Full Name",
  "ContactDetails": {
    "Email": "your.email@example.com",
    "Phone": "123-456-7890",
    "Address": "Your Address",
    "LinkedIn": "Your LinkedIn URL",
    "GitHub": "Your GitHub URL"
  },
  "ProfessionalSummary": "Your professional summary...",
  "WorkExperience": [
    {
      "Position": "Your Job Title",
      "Company": "Your Company",
      "Location": "City, State",
      "Period": "Start Date - End Date",
      "Responsibilities": [
        "Responsibility 1",
        "Responsibility 2",
        "Responsibility 3"
      ]
    },
    ...
  ],
  "EducationHistory": [
    {
      "Degree": "Your Degree",
      "Institution": "Your Institution",
      "Location": "City, State",
      "Period": "Start Date - End Date",
      "Details": [
        "Detail 1",
        "Detail 2"
      ]
    },
    ...
  ],
  "TechnicalSkills": [
    "Skill 1",
    "Skill 2",
    "Skill 3"
  ],
  "Certifications": [
    {
      "CertificationName": "Certification Name",
      "Issuer": "Issuing Organization",
      "Date": "Date"
    }
  ],
  "Projects": [
    {
      "ProjectName": "Project Title",
      "Description": "Project Description",
      "TechnologiesUsed": [
        "Technology 1",
        "Technology 2"
      ],
      "Link": "Project URL"
    },
    ...
  ]
}

Please convert the resume content provided above into the specified JSON format.
