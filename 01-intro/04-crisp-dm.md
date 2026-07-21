## 1.4 CRISP-DM

<a href="https://www.youtube.com/watch?v=dCa3JvmJbr0&list=PL3MmuxUbc_hIhxl5Ji8t4O6lPAOpHaCLR&index=5"><img src="images/thumbnail-1-04.jpg"></a>

[Slides](https://www.slideshare.net/AlexeyGrigorev/ml-zoomcamp-14-crispdm)


## Notes

CRISP-DM, which stands for Cross-Industry Standard Process for Data Mining, is an open standard process model that describes common approaches used by data mining experts. It is the most widely-used analytics model. Conceived in 1996, it became a European Union project under the ESPRIT funding initiative in 1997. The project was led by five companies: Integral Solutions Ltd (ISL), Teradata, Daimler AG, NCR Corporation and OHRA, an insurance company: 

1. **Business understanding:** 
   - What is the problem that the business want to understand?
   - Do we need ML for the project?
   - The goal of the project has to be measurable. 
   - It is better to ask questions now to reduce the number of iterations if possible
2. **Data understanding:** 
   - Analyse available data sources, understand what each columns represent semantically
   - Return on Business Understanding if data is either missing or ambiguous - **DON'T ASSUME**
3. **Data preparation:** 
   - Clean data, remove noise, discover and note book abnormal issue (formatting, missingness)
   - Convert the data to a tabular format so we can put it into ML
   - Provide clear steps and illustration along the way to present to business
4. **Modeling:** 
   - Train different models and choose the best one
   - If results are suspicious, return to Data Preparation to check:
      - Are features correctly calculated?
      - Are there data leakage occuring in the evaluation set?
      - Are there missing values or incorrect format?
5. **Evaluation:** 
   - Measure how well the model is performing using the chosen metric from the start
   - Analyse if the business problem has been solved using the model or not
      - If not then return to Business Understanding and analyse what is missing
      - Sometimes the plan/model is not work and you have to restart, that is **normal *and* epexected**
6. **Deployment:** 
   - Roll out to production to all the user
   - The evaluation and deployment often happen together - **online evaluation**. 

It is important to consider how maintainable the project is.
  
In general, ML projects require many iterations.

**Iteration:** 
* Start simple
* Learn from the feedback
* Improve

<table>
   <tr>
      <td>⚠️</td>
      <td>
         The notes are written by the community. <br>
         If you see an error here, please create a PR with a fix.
      </td>
   </tr>
</table>

* [Notes from Peter Ernicke](https://knowmledge.com/2023/09/12/ml-zoomcamp-2023-introduction-to-machine-learning-part-4/)

## Navigation

* [Machine Learning Zoomcamp course](../)
* [Lesson 1: Introduction to Machine Learning](./)
* Previous: [Supervised Machine Learning](03-supervised-ml.md)
* Next: [Model Selection Process](05-model-selection.md)
