# SYCL Project List

This is simply a curated list of SYCL based projects. It is designed to be used in other services, charting 
software etc.

## View Projects

[CLICK HERE TO VIEW PROJECTS IN DIFFERENT VIEWS](https://scottstraughan.github.io/sycl-project-list/)

You can view projects by opening the ```projects.json``` file or visiting 
[SYCL Project List](https://scottstraughan.github.io/sycl-project-list/) to view the GitHub pages rendered views.

## Add A Project

Edit the file ```projects.json``` and add the below json object into the ```projects``` array.

```
{
    "name": "Example SYCL Project",
    "date_created": "2020-05-02",
    "url": "https://github.com/scottstraughan/sycl-project-list",
    "type": "library",
    "short_description": "This is an example SYCL project.",
    "owner": {
       "name": "Codeplay Software Ltd",
       "url": "https://codeplay.com"
     },
    "licence": "MIT"
}
```

Create a pull request.
