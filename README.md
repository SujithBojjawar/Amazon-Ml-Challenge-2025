# ML Challenge 2025 Problem Statement

## Smart Product Pricing Challenge

In e-commerce, determining the optimal price point for products is crucial for marketplace success and customer satisfaction. Your challenge is to develop an ML solution that analyzes product details and predict the price of the product. The relationship between product attributes and pricing is complex - with factors like brand, specifications, product quantity directly influence pricing. Your task is to build a model that can analyze these product details holistically and suggest an optimal price.

**Team Name:** Team DataMinds. (Honestly I wasn't the one who came up with it. But still cool name)

**Team Members:** 
- [Sujith Bojjawar](https://www.linkedin.com/in/sujith-bojjawar-26b820256/)
- [Gayathri P](https://www.linkedin.com/in/gayathri-pch/) 
- [T Manas ](https://in.linkedin.com/in/t-manas-chakravarty-91958224b)  
- [Tejaswi Niharika](https://in.linkedin.com/in/relli-tejaswi-niharika-032696295)

### Data Description:

The dataset consists of the following columns:

1. **sample_id:** A unique identifier for the input sample
2. **catalog_content:** Text field containing title, product description and an Item Pack Quantity(IPQ) concatenated.
3. **image_link:** Public URL where the product image is available for download. 
   Example link - https://m.media-amazon.com/images/I/71XfHPR36-L.jpg
   To download images use `download_images` function from `src/utils.py`. See sample code in `src/test.ipynb`.
4. **price:** Price of the product (Target variable - only available in training data)

### Dataset Details:

- **Training Dataset:** 75k products with complete product details and prices
- **Test Set:** 75k products for final evaluation

### Our trials 
Numbered from Trial#001 onwards, the repo has all our trial notebooks stored. Starting from Gradient Boost to Fusion Net

### Docs:
Please refer to : https://docs.google.com/document/d/1px-qo-ZPwZIdNuDWyEl7LUUJc4KpvBM3K5Wf_HfelSI/edit?usp=sharing
And https://docs.google.com/document/d/1q1rM68oRUdhINxmXpYjBMsRldxoT_HAfFM7vB-OBRHI/edit?usp=sharing
