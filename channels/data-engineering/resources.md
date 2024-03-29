## Data Engineering Resources

Here is a fairly comprehensive list (contributed by the #data-engineering community)

### Roles in Data Engineering 

The following information was written by @dylan:

There are a lot of roles closely-related to data
engineering that oftentimes blur and bend based on 
company context, but touch on a lot of the same core 
problems.

A "traditional" data engineer role would be one in which
you're creating/maintaining ETL pipelines, filling up data
lakes/warehouses, and even doing a fair bit of database schema
design at every step. This role definition is expanding very 
quickly though, but if you asked a bunch of tech execs what a 
data engineer does, they'd likely say something like that.

Because data engineering is really the "glue" that keeps 
company-wide data operations together, it buts up against a 
lot of other technical roles in an organization. I'm going to 
try to list out the major ones, but please add to this list or
correct me if anything looks off base:

**Data science**: data engineers provide "care and feeding" to 
those folks who are training/running ML models or doing 
analytics work by providing them with the data they need; 
usually this requires a good understanding of where the
organization's data is stored, how it's shaped, and how it 
can be transformed so that it's useful to the data scientists 
who need it

**Machine learning engineering**: oftentimes machine learning 
models are built so that they can be retrained in an automated 
fashion after learning from data encountered in the wild, and 
there's also a large need for collating labeled/tagged data so 
it can be trained upon - data engineers bring their ETL skills 
to bear here often
Application engineering: data engineers often 
consume the data generated by application frontends/backends; 
often they're responsible for routing data generated by an 
application to an appropriate location like a data warehouse/lake

**DevSecOps**: automation is absolutely key to not hating your life 
if you're a data engineer; oftentimes an internal DevSecOps team 
will have a suite of tooling that a savvy data engineer can take
advantage of for data movement purposes; there's also often security/PII 
concerns when dealing with large chunks of data, so interacting with security 
teams is necessary in sufficiently large orgs

**Platform engineering**: there's a little grayness here due to some 
overlap with their DevSecOps kinfolk, but oftentimes the platform 
engineer types are the ones using Terraform, CloudFormation, and 
other IaC tools to manage cloud infra - if you're a data engineer, 
these tools can be extremely helpful in setting up systems to move 
data around

Data engineers service all those types of roles ^, and if you've had 
good experiences working with any of those groups, the extra perspective
 would likely make you a very effective data engineer!

### Newsletters/Blogs
- [Data Engineering Wiki](https://dataengineering.wiki/Index)
- [Data Engineering Weekly](https://www.dataengineeringweekly.com/)

### Books

### Courses

FYI, If you have a Denver Public library card, you can access [Udemy for Business](http://gale.udemy.com/) for free! 

### Podcasts

### Datasets 

The best way to learn is to DO! Here are some datasets to get you started: 

- [data.world](https://data.world/)
- [Kaggle](https://www.kaggle.com/datasets)

### Tools 

- [dbt](https://github.com/dbt-labs/dbt)
