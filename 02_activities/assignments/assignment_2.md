# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 

- Bad visualization:  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
      Source: Tableau Public – Countries with the Most Holidays in 2024
      Link: https://public.tableau.com/app/profile/mateusz.karmalski/viz/CountrieswiththeMostHolidaysin2024makeovermonday/Dashboard12
      Author: Mateusz Karmalski
      

      This visualization should be classified as a bad data visualization due to issues related to clarity, perceptual accuracy, and cognitive load. Although the dataset is valid, the design choices hinder effective communication of the main message.
      
      First, the visualization suffers from visual clutter and overplotting. It combines multiple elements—including thin vertical bars, reference lines, text annotations, and a world map—in a single view.Unnecessary visual elements increase cognitive load and make it harder for us to extract insights efficiently.
      
      Second, there is a lack of clear visual hierarchy. While the title emphasizes “countries with the most holidays,” all countries are presented with similar visual weight, and there is no clear ranking or ordering. This violates best practices in visual emphasis, as key comparisons are not immediately apparent to the viewer.
      
      Third, the visualization relies on redundant and inefficient visual encodings. The number of holidays is represented simultaneously through bar height, map markers, and guide lines.Redundant encodings should only be used when they add clarity; in this case, they introduce confusion without improving understanding.
      
      Together, these issues reduce perceptual accuracy and make comparisons across countries difficult, classifying this visualization as ineffective.

      ```
    - How could this data visualization have been improved?  
      ```
      First, the visualization could be improved by simplifying the design, such as using a ranked horizontal bar chart to display only the top countries. This would reduce clutter and improve comparability.
      
      Second, the removal of the world map or separating it into a secondary visualization would lower cognitive load and allow us to focus on the primary comparison, aligning with principles of clarity and minimalism.
      
      ```

- Good visualization:  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
      Source: Tableau Public – Degrees, Certificates and Diplomas: Annual Count of Awards
      Link: https://public.tableau.com/app/profile/mcc.rpie/viz/AnnualDegreesandCertificates_16487718324400/Awards
      Publisher: MiraCosta College

      This visualization can be classified as a good data visualization because it clearly communicates trends in academic awards over time while following key data visualization principles. The use of a stacked bar chart is appropriate for showing both overall totals and the composition of different credential types across academic years. This effectively supports part-to-whole comparison, which is a recommended practice for categorical breakdowns.

      A second strength is the clear visual hierarchy. Total award counts are displayed prominently above each bar, allowing viewers to quickly compare overall output between years. At the same time, consistent color encoding helps distinguish different award categories, making it easier to recognize patterns without excessive cognitive effort and it is aligns with visual emphasis and efficient encoding.

      Third, the visualization supports perceptual accuracy and readability. All bars share a common baseline, enabling accurate comparison across years. Labels, legends, and axes are clearly presented, and the option to use a high-contrast color scheme improves accessibility. The inclusion of a data table beneath the chart further enhances transparency by allowing users to verify exact values, which supports trustworthy data communication.

      Overall, the visualization balances detail and clarity, communicates trends effectively, and applies encoding, hierarchy, and accessibility.

      ```
    - How could this data visualization have been improved?  
      ```
      Despite its strengths, there are opportunities for improvement. First, stacked bar charts make it difficult to compare changes in individual categories over time, since only one segment shares a common baseline. Providing an alternative view, such as small multiple bar charts or a line chart for selected award types, would improve comparability and analytical clarity.

      Second, the visualization could benefit from brief annotations or highlights that draw attention to notable changes or trends across years. Course materials emphasize that annotations can reduce cognitive load by guiding viewers toward meaningful insights rather than requiring them to search for patterns independently.

      These adjustments would enhance interpretability while preserving the visualization’s overall effectiveness.
      
      ```
- Word count should not exceed (as a maximum) 500 words for each visualization (i.e. 
300 words for your good example and 500 for your bad example)

### Why am I doing this assignment?:

- This assignment ensures active participation in the course, and assesses the learning outcomes
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story

### Rubric:

| Component               | Scoring   | Requirement                                                 |
|-------------------------|-----------|-------------------------------------------------------------|
| Data viz classification and justification | Complete/Incomplete | - Data viz are clearly classified as good or bad<br />- At least three reasons for each classification are provided<br />- Reasoning is supported by course content or scholarly sources |
| Suggested improvements  | Complete/Incomplete | - At least two suggestions for improvement<br />- Suggestions are supported by course content or scholarly sources |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 01/26/2026`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (assignment_2.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
