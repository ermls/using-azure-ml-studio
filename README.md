# using-azure-ml-studio
Using Azure ML studio to build a regression pipeline

Here I go through the “Create a regression model with Azure Machine Learning designer” training module. I am describing what I am doing as I go through the lesson to
demonstrate my ability to create machine learning pipelines using Azure Machine Learning Studio.

In practice, I would use Power Platform to call the service through connectors or Power Automate flows. The API can also be called through code.

1. Create the ML resource

![1](https://user-images.githubusercontent.com/83891373/188259442-06a8477a-8a6b-4518-83fa-518ff563a9a5.jpg)

2. Enter the ML Studio home screen

![2](https://user-images.githubusercontent.com/83891373/188259456-4a024720-aea2-441e-ad68-c06ea6836d21.jpg)

3. Set up the compute cluster

![3](https://user-images.githubusercontent.com/83891373/188259458-888ca8d1-09d9-45c1-9d3a-4a83d9478a97.jpg)

![4](https://user-images.githubusercontent.com/83891373/188259461-0fab4b45-d47d-4938-8b51-a79bc73a4064.png)

4. Import the .csv file and select columns

![6](https://user-images.githubusercontent.com/83891373/188259497-082a9088-d905-4c62-ae61-85094e390b2e.jpg)

![7](https://user-images.githubusercontent.com/83891373/188259499-b3453443-3add-434f-80af-c8d9d6c70ca9.jpg)

5. Clean data

![8](https://user-images.githubusercontent.com/83891373/188259502-6c874f20-55e3-48fd-9b0e-bd4e002ec1f7.jpg)

6. Normalize Data

![9](https://user-images.githubusercontent.com/83891373/188259504-75ba20c5-5d09-4805-ba27-d78005afcaaf.jpg)

7. Split Data

![10](https://user-images.githubusercontent.com/83891373/188259508-eb75a316-3eec-4df2-a962-1a9e24dab6df.jpg)

8. Train model to predict price labels using linear regression, then score model.

![11](https://user-images.githubusercontent.com/83891373/188259537-8ea959e6-9981-4a8d-baea-1d2587954fbd.jpg)

9. Run model.

![12](https://user-images.githubusercontent.com/83891373/188259543-50215304-54ee-4ef0-aee9-489313dd1be0.jpg)

10. Evaluate model.

![13](https://user-images.githubusercontent.com/83891373/188259546-133bd000-c3ae-4338-8652-a5ca0e0bf278.jpg)

![14](https://user-images.githubusercontent.com/83891373/188259551-e3ed43e9-65c9-44ed-adc6-d38596e5578a.jpg)

11. Create inference pipeline.

![16](https://user-images.githubusercontent.com/83891373/188259645-29937fba-2e3b-4e62-a767-194377c09e4b.jpg)

![17](https://user-images.githubusercontent.com/83891373/188259649-602af4d7-6656-433a-a34a-bb8ddd905035.jpg)

12. Evaluate results of test data in "Enter Data Manually" component to make sure everything works

![18](https://user-images.githubusercontent.com/83891373/188259758-f1b85532-476a-4fef-bcd8-1ee8b20a0477.jpg)


12. Deploy model to endpoint

![19](https://user-images.githubusercontent.com/83891373/188259765-643fd95b-c958-4086-b132-c73ff6e15be0.jpg)

![20](https://user-images.githubusercontent.com/83891373/188260031-3f829d52-b5b0-4546-be15-d2d1c2de76d0.jpg)

13. Test

![21](https://user-images.githubusercontent.com/83891373/188260033-9370f51e-cd6b-47e0-a317-4b653eff4492.jpg)
