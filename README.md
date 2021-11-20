# sampleProjectPySpark

To Do

PySparkApp
1. Create a PySpark app on local computer which reads data from two different files csv as well as json located at S3 location.
2. Apply simple join and aggregation.
3. Store the result on S3 at the output location.

4. Run on Colab
5. Run on Docker Spark Container
6. Run on EMR

7. Create a development main branch and commit the working code.
8. Clone the code to the local again freshly make one changes lets say to include new column in the output file.
9. Test the code locally

10. Commit the changes to master branch, not this should trigger a aws code pipeline.

11. Codepipeline for Test Execution
12. Create the Container having all the dependencies of the application and pytest script to test different test cases.
13. Once all the test is passed. Then should send a notification to all stake holders.
14. Production Deployment pipline can be triggered manually or after a approval trigger code. 
15. For Batch Pipeline - Once can deploy the tested code on the respective directory for the existing AWS host services like EMR.
16. For Real-time/ API based pipline, you may want to follow Blue Green Stragy to make the service downtime minimal.



      

