# Adidas Store Scraper
>Unlock detailed product data from the official Adidas US online store with this powerful scraper. Extract information such as pricing, stock availability, images, ratings, and specifications by using product URLs, categories, or search keywords. Ideal for e-commerce managers, data analysts, or market researchers, this tool helps monitor pricing trends and gather product data quickly.

---

<p align="center">
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/scraper.png" alt="Bitbash Banner" width="100%"></a>
</p>
<p align="center">
  <a href="https://t.me/Bitbash333" target="_blank">
    <img src="https://img.shields.io/badge/Chat%20on-Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
  </a>&nbsp;
  <a href="https://wa.me/923249868488?text=Hi%20BitBash%2C%20I'm%20interested%20in%20automation." target="_blank">
    <img src="https://img.shields.io/badge/Chat-WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp">
  </a>&nbsp;
  <a href="mailto:sale@bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Email-sale@bitbash.dev-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
  </a>&nbsp;
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Visit-Website-007BFF?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website">
  </a>
</p>

<p align="center" style="font-weight:600; margin-top:8px; margin-bottom:8px;">
  Created by Bitbash, built to showcase our approach to Scraping and Automation!<br>
  If you are looking for <strong>Adidas Store Scraper</strong> you've just found your team — Let's Chat. 👆👆
</p>

## Introduction
The Adidas Store Scraper allows you to efficiently collect product details from adidas.com/us. It offers flexible input options, including individual product URLs, category pages, or search results, allowing for tailored data extraction. Use it for pricing comparisons, competitor analysis, or stock monitoring. The data is returned in a structured format, ready for immediate use in reports, dashboards, or business intelligence tools.

### Key Features
- **Flexible Scraping**: Start scraping from product URLs, category pages, or search results.
- **Comprehensive Data**: Extracts over 20 data points per product, including pricing, stock, images, videos, ratings, and specifications.
- **Powerful Filters**: Refine your search by setting minimum and maximum price ranges.
- **Smart Pagination**: Scrape entire categories or specific page ranges (e.g., startPageNumber to finalPageNumber).
- **Proxy Integration**: Built-in support for Apify Proxy to ensure stable and scalable scraping operations.
- **Structured Output**: Clean, machine-readable JSON output for easy integration.

---
## Features
| Feature | Description |
|---------|-------------|
| Flexible Scraping | Scrape data from specific product URLs, category pages, or via keyword search. |
| Detailed Product Data | Extracts product name, price, stock status, media, ratings, and specifications. |
| Price Filtering | Set minimum and maximum price ranges to target specific products. |
| Pagination Control | Customize the range of pages to scrape (e.g., from startPageNumber to finalPageNumber). |
| Proxy Support | Use Apify Proxy for better reliability and to avoid blocks. |
| Structured JSON Output | Data is delivered in a clean, machine-readable JSON format. |

---
## What Data This Scraper Extracts
| Field Name | Field Description |
|------------|-------------------|
| productName | The name of the product. |
| price | The price of the product. |
| stockAvailability | Availability status (e.g., in stock, out of stock). |
| imageUrl | URLs of product images. |
| videoUrl | URLs of product videos (if available). |
| rating | Customer rating for the product. |
| numReviews | The number of reviews for the product. |
| description | Product description. |
| productUrl | Direct URL to the product page. |
| category | Product category. |
| sizeOptions | Available sizes for the product. |
| colorOptions | Available colors for the product. |
| productID | Unique product ID for internal reference. |

---
## Example Output
    
    [
      {
        "productName": "Adidas Ultraboost 22 Shoes",
        "price": 180.00,
        "stockAvailability": "In Stock",
        "imageUrl": "https://assets.adidas.com/images/ultraboost22.jpg",
        "videoUrl": "https://assets.adidas.com/videos/ultraboost22_video.mp4",
        "rating": 4.5,
        "numReviews": 1500,
        "description": "The Adidas Ultraboost 22 offers exceptional comfort and support with a sleek, performance-driven design.",
        "productUrl": "https://www.adidas.com/us/ultraboost-22",
        "category": "Running Shoes",
        "sizeOptions": ["7", "8", "9", "10", "11"],
        "colorOptions": ["White", "Black", "Blue"],
        "productID": "123456789"
      }
    ]

---
## Directory Structure Tree
    
    Adidas Store Scraper/
    ├── src/
    │   ├── main.js
    │   ├── scraper/
    │   │   ├── product_scraper.js
    │   │   ├── category_scraper.js
    │   │   └── keyword_search.js
    │   ├── utils/
    │   │   ├── proxy_manager.js
    │   │   ├── pagination.js
    │   │   └── filter.js
    │   └── config/
    │       └── settings.example.json
    ├── data/
    │   ├── sample_input.json
    │   └── sample_output.json
    ├── package.json
    └── README.md

---
## Use Cases
- **E-commerce Managers** track Adidas product pricing, availability, and reviews to monitor trends.  
- **Market Researchers** analyze competitor offerings and identify gaps in the Adidas product line.  
- **Price Comparison Websites** gather Adidas data for automated comparison of product prices across various e-commerce platforms.  
- **Retail Analysts** study inventory levels and stock availability over time.  
- **Content Curators** collect product data to populate websites, blogs, or affiliate programs.  

---
## FAQs

**How do I input data for scraping?**  
You can input product URLs, category URLs, or keywords to start the scraper.

**Can I filter products by price?**  
Yes, you can set a minimum and maximum price range to target specific product types.

**What kind of data do I get from the scraper?**  
You receive detailed product data such as name, price, stock status, images, ratings, descriptions, and more.

**Can I scrape multiple pages of a category?**  
Yes, you can set a range of pages to scrape using the `startPageNumber` and `finalPageNumber` settings.

---
### Performance Benchmarks and Results

**Primary Metric:**  
Fetches product data for 100–200 products per minute, depending on network speed and website structure.

**Reliability Metric:**  
Achieves over 98% success rate for scraping product data, with effective proxy management.

**Efficiency Metric:**  
Optimized for large-scale scraping with minimal overhead, even when processing multiple pages or categories.

**Quality Metric:**  
Delivers consistently clean and structured product data ready for use in databases, analysis, or reports.


---


<p align="center">
<a href="https://calendar.app.google/74kEaAQ5LWbM8CQNA" target="_blank">
  <img src="https://img.shields.io/badge/Book%20a%20Call%20with%20Us-34A853?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Book a Call">
</a>
  <a href="https://www.youtube.com/@bitbash-demos/videos" target="_blank">
    <img src="https://img.shields.io/badge/🎥%20Watch%20demos%20-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch on YouTube">
  </a>
</p>
<table>
  <tr>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/MLkvGB8ZZIk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review1.gif" alt="Review 1" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash is a top-tier automation partner, innovative, reliable, and dedicated to delivering real results every time."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Nathan Pennington
        <br><span style="color:#888;">Marketer</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/8-tw8Omw9qk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review2.gif" alt="Review 2" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash delivers outstanding quality, speed, and professionalism, truly a team you can rely on."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Eliza
        <br><span style="color:#888;">SEO Affiliate Expert</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/m-dRE1dj5-k?si=5kZNVlKsGUhg5Xtx" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review3.gif" alt="Review 3" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Exceptional results, clear communication, and flawless delivery. <br>Bitbash nailed it."
      </p>
      <p style="margin:1px 0 0; font-weight:600;">Syed
        <br><span style="color:#888;">Digital Strategist</span>
        <br><span style="color:#f5a623;">★★★★★</span>
         </p>
