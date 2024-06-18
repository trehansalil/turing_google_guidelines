**1. Make sure that you've checked the boxes below before you submit MR:**

- **Step 1:**

- Update "query" to "User_query in all notebooks.
- Always Check if correct file name, Capability and Tags are mentioned or not.

  -  EAP:
      - EAP should start with calling out relevant columns.
      - The plan should be more specific and concise, It should mention briefly the problem and what are the next steps.
      - When in case of numeric column if conversion is not required then mention the same.
      - File name should be mentione in double quotes.
      - Only required cleaning should be mentioned.
      - Should not use plural pronouns. 

  -  CI:
      - Check if CI is following the EAP.
      - CI should at least have 3 points.
      - Use “Convert to numeric” instead of “Convert to float”.
      - Ensure the CODER_INSTRUCTION have appropriate subsections such as **Tidy the data** and **Transform and aggregate the data**.
      - It's better to separate the data transformation and visualization instruction's into two different subheadings ( Transform the data and Visualize the data).
      - If there is some cleaning or conversion it should be included under subhead **Tidy the data**.
      - `df.info`, `df.head`, column name and dataframe name should be in back ticks.
      - CI should also follow same styling rule as mentioned in EAP.
      - Datetime conversion should include in CI also.
      - Commas ','and point '.' should be in single quotes.
      - No need of mentioning the methods in CI
      - At the end always mention display the result.

  -  Last Few Checks:
      - Check if correct library is imported.
      - No need to re-import the library.
      - Check if code is following the CI.
      - Final response should be complete and contain all the details required to answer the user query. 
      - If there is table in ANSWER_QUERY then check if it is formatted correctly.
      - In code comment, it should start with Uppercase.
      - In code each line should have comment above to it.
      - Should not contain file name in ANSWER_QUERY that is final response.
      - Should not contain Image tags and follow up suggestion in final response.




- **Step 2:**

- Update "query" to "User_query in all notebooks.
- The 1st turn in a multiturn should have 'Single Turn' Tag and all subsequent turns should have the tag 'Multi Turn'.
- "previous_turn_number" is specific to each file in the metadata block.
- **previous_turn_number for a file basically represents: How many User queries+Answer queries (U+G) ago did that particular file appear for the first time in the conversation**


  -  EAP:
      - EAP should start with calling out relevant columns.
      - The plan should be more specific and concise, It should mention briefly the problem and what are the next steps.
      - When in case of numeric column if conversion is not required then mention the same.
      - File name should be mentione in double quotes.
      - Only required cleaning should be mentioned.
      - Should not use plural pronouns. 

  -  CI:
      - Check if CI is following the EAP.
      - CI should at least have 3 points.
      - Use “Convert to numeric” instead of “Convert to float”.
      - Ensure the CODER_INSTRUCTION have appropriate subsections such as **Tidy the data** and **Transform and aggregate the data**.
      -  It's better to separate the data transformation and visualization instruction's into two different subheadings ( Transform the data and Visualize the data).
      - If there is some cleaning or conversion it should be included under subhead **Tidy the data**.
      - `df.info`, `df.head`, column name and dataframe name should be in back ticks.
      - CI should also follow same styling rule as mentioned in EAP.
      - Datetime conversion should include in CI also.
      - Commas ','and point '.' should be in single quotes.
      - No need of mentioning the methods in CI
      - At the end always mention display the result.

  -  Last Few Checks:
      - Check if correct library is imported.
      - No need to re-import the library.
      - Check if code is following the CI.
      - Final response should be complete and contain all the details required to answer the user query without much verbose. 
      - If there is table in ANSWER_QUERY then check if it is formatted correctly.
      - In code each line should have comment above to it.
      - Should not contain file name in ANSWER_QUERY that is final response.
      - Should not contain Image tags and follow up suggestion in final response.
    


Step 3:

 -  EAP:
      - EAP should start with calling out relevant columns.
      - The plan should be more specific and concise, It should mention briefly the problem and what are the next steps.
      - When in case of numeric column if conversion is not required then mention the same.
      - File name should be mentione in double quotes.
      - Only required cleaning should be mentioned.
      - Should not use plural pronouns. 
      - Good practice to call out column name.

  -  CI:
      - Check if CI is following the EAP.
      - CI should at least have 3 points.
      - Use “Convert to numeric” instead of “Convert to float”.
      - Ensure the CODER_INSTRUCTION have appropriate subsections such as **Tidy the data** and **Transform and aggregate the data**.
      -  It's better to separate the data transformation and visualization instruction's into two different subheadings ( Transform the data and Visualize the data).
      - If there is some cleaning or conversion it should be included under subhead **Tidy the data**.
      - `df.info`, `df.head`, column name and dataframe name should be in back ticks.
      - CI should also follow same styling rule as mentioned in EAP.
      - Datetime conversion should include in CI also.
      - Commas ','and point '.' should be in single quotes.
      - No need of mentioning the methods in CI
      - At the end always mention display the result.

  -  Last Few Checks:
      - Check if code is following the CI.
      - Check if it is hallicinating

      
<!-- - [ ] I have updated the documentation to reflect my changes.
- [ ] I have resolved merge conflicts before submitting this MR. -->

**2. Which issues that we have faced in the past?**

- Due to blury screen on Anydesk, one time I got comnfused with single quote and back ticks. 

**3. CHANGELOG/Release Notes**

- Take your time thinking before writing about what you have learned.
- Please take a look at the documents shared on the Slack channel.
- You're free to re-structure this, but send an MR to merge your work with mine. 
