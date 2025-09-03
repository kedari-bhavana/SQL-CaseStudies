🛍️ TheLook Ecommerce – SQL Case Studies

Welcome to the TheLook Ecommerce case study series! 🎉
Here, we’ll use SQL on Google BigQuery to explore real-world business problems through data. Think of it as a sandbox where we play “data detective” 🕵️‍♀️ while also practicing industrial-grade SQL.

🔗 Platform: BigQuery

We’re running all our queries on Google BigQuery, which gives us access to a treasure chest of public datasets — no messy setup required, just fire up the query editor and go! 🚀

📦 Dataset: TheLook Ecommerce

TheLook is a realistic but synthetic e-commerce dataset created by Google Cloud’s data team.
It was designed to mimic a fashion retail business — customers browse, buy, return products, and generate events.
So while nobody actually bought that pair of neon socks 🧦 you’ll see in the data, the dataset behaves just like real life!

This makes it perfect for practicing:

Sales analytics 📊

Customer behavior analysis 👥

Inventory & supply chain insights 🚚

Marketing funnel tracking 📈

🗂️ Tables Inside

Here are the stars of our show:

distribution_centers – locations where products are stored and shipped from.

events – user interactions like browsing, clicking, adding to cart, or purchasing.

inventory_items – stock details of products available at each distribution center.

order_items – the nitty-gritty of what items were bought, quantities, prices.

orders – higher-level info about each order (timestamps, users, status).

products – the product catalog: categories, brands, pricing.

thelook_ecommerce_table – a catch-all table with combined information (think “summary view”).

users – customer demographics: age, gender, location.

🎯 Why This Dataset Rocks

Free & accessible → thanks BigQuery 🙏.

Looks like a real business → insights are meaningful (not toy data).

Perfect for case studies → we can ask genuine business questions like:

Who are our repeat customers?

Which product categories drive the most revenue?

Are there seasonal spikes in orders?

How healthy is our inventory pipeline?

Stay tuned — each query here will answer a real business question with SQL and then interpret what the numbers actually mean 📖.
