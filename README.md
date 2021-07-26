# SYCL Project List

This is simply a curated list of SYCL based projects. It is designed to be used in other services, charting 
software etc.

## List of Views

Below is a short list of different views using the ```projects.json``` file as its data source.

* [Accumulation Graph of SYCL Projects/Year](https://scottstraughan.github.io/sycl-project-list/views/accumulated-projects-line-graph.html)
* Coming Soon!

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
