{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "f038f9ed",
   "metadata": {},
   "source": [
    "# Classification Project\n",
    "### Why are Customers Churning?\n",
    "\n",
    "This project was built using python\n",
    "\n",
    "Goal:\n",
    "Find out why customers are churning\n",
    "Use data science methodologies. \n",
    "\n",
    "### Questions we are interested in:\n",
    "When are customers most likely to churn?\n",
    "Which features affect churn the most?\n",
    "Is there a price threshold that increases churn per feature?\n",
    "What does the churn rate look like after the 12th month?\n",
    "\n",
    "#### The goals of the project are to answer the questions and deliver the following:\n",
    "\n",
    "A Complete Jupyter Notebook Report showing the step-by-step process and statistical analysis of driver(s) of customer churn.\n",
    "a README.md file containing:\n",
    "project description with goals\n",
    "a data dictionary\n",
    "project planning (lay out your process through the data science pipeline)\n",
    "explanation of how someone else can recreate your project and findings\n",
    "key findings and takeaways from your project.\n",
    "a CSV file with customer_id, probability of churn, and prediction of churn.\n",
    "individual modules, .py files, that hold your functions to acquire and prepare your data.\n",
    "Clearly state your starting hypotheses (and add the testing of these to your task list).\n",
    "\n",
    "### Data Dictionary\n",
    "\n",
    "Attribute                      Definition\t                                                Data Type\n",
    "customer_id                    Alpha-numeric ID that identifies each customer\t            object\n",
    "online_security\t               Indicates if a customer has online security add-on\t        int64\n",
    "online_backup\t               Indicates if a customer has online backups add-on\t        int64\n",
    "device_protection\t           Indicates if a customer has a protection plan for devices\tint64\n",
    "tech_support\t               Indicates whether a customer has technical support add-on\tint64\n",
    "streaming_tv\t               Indicates if a customer uses internet to stream tv\t        int64\n",
    "streaming_movies\t           Indicates if a customer uses internet to stream movies\t    int64\n",
    "internet_service_type\t       Indicates the type of internet service a customer has\t    object\n",
    "dsl_internet\t               Indicates if the customer has dsl internet or not\t        uint8\n",
    "fiber_optic_internet\t       Indicates if the customer has fiber optic internet or not\tuint8\n",
    "\n",
    "#### Target is Churn. Has the customer stayed or terminated service?\n",
    "\n",
    "### Data Accusation \n",
    "\n",
    "function name: acquire.py\n",
    "\n",
    "### Data Preparation \n",
    "\n",
    "function name: prepare.py\n",
    "\n",
    "### Data Exploration \n",
    "#### Feature engineering\n",
    "Binning 'tenure' feature into 6 ranges:\n",
    "\n",
    "0-12 months --> '0-1 years'\n",
    "12-24 months --> '1-2 years'\n",
    "24-36 months --> '2-3 years'\n",
    "36-48 months --> '3-4 years'\n",
    "48-60 months --> '4-5 years'\n",
    "More than 60 months --> 'more than 5 years'\n",
    "\n",
    "\n",
    "#### Observations \n",
    "\n",
    "There are significantly more non-senior citizens than senior citizens\n",
    "There are a lot more customers with dependents\n",
    "More customers are Month-to-month than in contracts\n",
    "Electronis check is the most popular payment method\n",
    "\n",
    "### Key Takaways\n",
    "It is clear that fewer people churn when they have more online services.\n",
    "\n",
    "#### What can we do now?\n",
    "\n",
    "Promote online services into bundled packages:\n",
    "For instance: the \"Security package\" will contain: online_security, online_backup, device_protection and tech_support\n",
    "Along with \"Streaming package\" that will contain: streaming_tv, streaming_movies, and tech_support as well.\n",
    "\n",
    "#### To Reproduce:\n",
    "\n",
    "You will need the following:\n",
    "\n",
    "1. env.py with credentials\n",
    "2. Python Modules(Numpy, Pandas, Sklearn, Seanorn, etc...)\n",
    "3. The files acquire.py, prepare.py and the jupyter notebook.\n",
    "\n",
    "\n"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.9.12"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
