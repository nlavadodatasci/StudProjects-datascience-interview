# Student Projects - Data Science Interview Challenges

---

## **Introduction**
Welcome to the Students' Interview Challenges repository! This collection of challenges is designed to assess your data science skills, creativity, and problem-solving abilities. By participating, you’ll have the opportunity to showcase your expertise and potentially join ongoing projects supervised by our team.

Our team specializes in leveraging data to solve complex real-world problems across industries. We value innovation, rigorous methodology, and clear communication, and we’re looking for students who share this mindset. To learn more about me, visit my [LinkedIn](https://www.linkedin.com/in/nuno-lavado-%F0%9F%94%B7-84541762/) and [CienciaVitae](https://www.cienciavitae.pt/portal/en/361B-FA5B-4EBF).

---

## **Challenge Overview**
Each challenge in this repository is inspired by real-world scenarios encountered in our projects. The challenges focus on applying data science techniques such as:
- **Predictive Modeling**
- **Time Series Analysis**
- **Clustering and Classification**
- **Data Cleaning and Preprocessing**
- **Exploratory Data Analysis (EDA)**
- **Optimization and Decision Making**

These tasks aim to simulate practical problems, giving you a taste of the challenges you might face while working on our projects.

---

## **Goals**
The purpose of these challenges is to:
1. Evaluate your ability to solve complex data problems using innovative methods.
2. Assess your technical proficiency in handling diverse datasets and tools.
3. Select motivated and talented individuals to collaborate on cutting-edge data science projects.

---

## **Dataset Description**
Each challenge provides:
- **Problem Context**: A description of the business problem or use case.
- **Dataset**: A structured dataset (or datasets) to analyze and solve the problem.
- **Deliverables**: Specific outputs expected, such as predictions, insights, or a prototype model.

All datasets are for challenge purposes only and are not to be used outside this repository.

---

## **Evaluation Criteria**
Your submissions will be reviewed based on:
1. **Accuracy**: Quality and effectiveness of your solution.
2. **Innovation**: Novelty and creativity in your approach.
3. **Clarity**: How well you document your process, assumptions, and findings.
4. **Reproducibility**: Whether your results can be replicated using your code and methodology.

---

## **Submission Guidelines**
To participate:
1. Fork this repository and work on the assigned challenge.
2. Submit your solution as a pull request before the specified deadline.
3. Include the following in your submission:
   - **Code**: Well-structured and commented scripts.
   - **Documentation**: A concise report detailing your approach, assumptions, and results.
   - **Results**: Your predictions, visualizations, and any additional insights.

If selected, you may be invited for a brief presentation of your solution, followed by a discussion about the challenges you encountered and the methods you used.

---

If students want to clone only a specific folder from the repository (e.g., for a specific challenge), they can use **Git Sparse Checkout**. Here's how you can update the "Getting Started" section to include this information:

---

## **Getting Started**
1. **Clone the Repository**: You can either clone the entire repository or just a specific challenge folder. To clone the repository:
   ```bash
   git clone https://github.com/nlavadodatasci/StudProjects-datascience-interview.git
   ```

2. **Clone Only a Specific Folder** (Optional): If you only want to clone a specific challenge folder, follow these steps:
   - Initialize a sparse-checkout Git clone:
     ```bash
     git init <local-folder-name>
     cd <local-folder-name>
     git remote add origin https://github.com/nlavadodatasci/StudProjects-datascience-interview.git
     git config core.sparseCheckout true
     ```
   - Specify the folder you want to clone (replace `<challenge-folder>` with the desired folder name):
     ```bash
     echo "<challenge-folder>/" >> .git/info/sparse-checkout
     ```
   - Pull the specified folder:
     ```bash
     git pull origin main
     ```

   For example, if the folder name is `challenge1`, the commands would look like:
   ```bash
   echo "challenge1/" >> .git/info/sparse-checkout
   git pull origin main
   ```

3. **Explore the Challenge**: Navigate to the folder and read the README file for specific instructions:
   ```bash
   cd <challenge-folder>
   ```

4. **Set Up the Environment**: The challenge folder might contain the necessary files for setting up dependencies. Use the provided `requirements.txt` or `poetry.lock` file to install dependencies:
   - Using `pip`:
     ```bash
     pip install -r requirements.txt
     ```
   - Using `poetry`:
     ```bash
     poetry install
     ```

5. **Work on Your Solution**: Develop your solution using the tools and libraries of your choice. Make sure to save your code and documentation within the same folder.

---

## **Support**
If you have any questions or need clarification, please open an issue in this repository or contact us at [nlavadodatasci@gmail.com](nlavadodatasci@gmail.com).

Good luck, and we look forward to seeing your innovative solutions!

--- 
