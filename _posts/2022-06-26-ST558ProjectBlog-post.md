Project1 Blog Post
================
Shan Luo
2022-06-26

``` r
rmarkdown::render("/Users/sl666/Desktop/ST558/ShanLLL52.github.io/_Rmd/2022-06-26-ST558ProjectBlog-post.Rmd", 
          output_format = "github_document", 
          output_dir = "/Users/sl666/Desktop/ST558/ShanLLL52.github.io/_posts",
          output_options = list(
            html_preview = FALSE))
```

## ST558 Project1 Blog Post

I find some interesting information. Firstly, in China, Hong Kong has
largest number of confirmed and deaths case. Secondly, Hainan province
have a relatively high death rate. Thirdly, there are 7 provinces that
have confirmed case less than 500. Tibet only has 1 confirmed case.

I checked all APIs and their endpoints. And I realized that it was very
important for me to have the background knowledge for these APIs. I
firstly decided to do the financial data, but as I looked into the data,
I realized that I had little knowledge about the stock market.
Similarly, for most of APIs, I thought that it took time to
understanding the data. Thus, I chose COVID API.

I felt that the most difficult part is to create the functions to query
the endpoint data. Although the basic knowledge was not too hard, it
still took relatively long time to get the function done. When I did
EDA, it was hard to make the visualization since the data was widely
spread. There are extremely large number of confirmed and deaths case
and extremely small number of confirmed and deaths case.

If I do a similar project in the future, I will firstly search enough
information about the data and get a good understanding. I will try to
create a better wrapper function to query the data. Also, I will think
about some research questions about the corresponding data and try to
answer them after the analysis.

[`Regular Repo`](https://github.com/ShanLLL52/ShanLLL52.github.io)

[\`Project1 Repo](https://github.com/ShanLLL52/ST558Project1)
