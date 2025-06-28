**Disclaimer:** This dataset is a synthesized collection of data created for academic and educational purposes only. It does not represent real-world operational data from any specific company.

## ecommerce-logistics-dataset-vn
Dataset for analyzing e-commerce logistics and inventory management in Vietnam, covering inventory, SKU masterdata, and vendor information for platforms like Shopee, Lazada, Tiki, TikTok.

# UpBase - E-commerce Logistics & Inventory Management Dataset
**Context:**
<br>This dataset is provided to simulate the operational environment of **UpBase**, an e-commerce enabler navigating the booming e-commerce market in Vietnam and globally. With significant annual growth (20-25% in Vietnam), driven by platforms like Shopee and TikTok, the market presents both opportunities and challenges for enablers like **UpBase**. Key global trends include digital payments, omnichannel sales, and personalized customer experiences, with the Asia-Pacific region leading market growth.

<br>However, **UpBase's** order fulfillment process faces significant challenges, especially during peak seasons (e.g., Double Day sales, Tet holiday), where sales can increase up to fivefold. These challenges include:
<br>- Inefficiencies due to manual processes and increased error risk.
<br>- Lack of tools for quick, data-driven decision-making and real-time tracking.
<br>- Difficulties in demand forecasting and strategic planning.
<br>- Poor transparency, trackability, and inter-departmental data integration.

<br>This dataset is intended to help analyze **UpBase's** operations, extract actionable insights, evaluate the value of platform data, and develop strategies to optimize logistics, manage inventory, and improve overall efficiency, particularly in preparation for high-demand periods.

**Dataset Structure:**
<br>The dataset consists of an Excel file with three distinct sheets, providing a comprehensive view of **UpBase's** e-commerce operations:

1.  **Inventory Data:**
    *   **Sku_name:** Name of the Stock Keeping Unit.
    *   **Sku_code:** Unique code for the SKU.
    *   **shop_account:** The e-commerce shop account identifier.
    *   **Tiki, Lazada, Shopee, TikTok:** Stock levels for each respective platform.
    *   **Tiki demand per month, Lazada demand per month, Shopee demand per month, TikTok demand per month:** Estimated monthly demand for the SKU on each platform.
    *   **DOITarget (days):** Days Of Inventory target.
    *   **Vendor:** The supplier of the SKU.
    *   **Brand:** The brand of the SKU.
    *   **Purpose:** Contains inventory levels, multi-channel demand forecasts, and supplier information for each SKU managed by **UpBase**.

2.  **SKU Masterdata:**
    *   **Sku Code:** Unique code for the Stock Keeping Unit (links to Inventory Data).
    *   **Sku Name:** Full name of the SKU.
    *   **SKU Short Name:** Abbreviated name for the SKU.
    *   **Primary Vendor:** Main supplier for the SKU.
    *   **Brand:** Brand of the SKU.
    *   **Sale Price:** Retail price of the SKU.
    *   **Base Cost:** Cost price of the SKU for **UpBase**.
    *   **Purpose:** Provides a detailed catalog of all SKUs sold by **UpBase**, including naming conventions, primary vendor, brand, and pricing information.

3.  **VendorMasterdata:**
    *   **SHOP_ACCOUNT:** The e-commerce shop account identifier (links to Inventory Data).
    *   **VENDOR:** Vendor identifier (links to Inventory Data).
    *   **BRAND:** Brand associated with the vendor for that shop account.
    *   **Vendor Name:** Full name of the vendor.
    *   **Shipping Adress:** Shipping address of the vendor.
    *   **Payment Terms (per week):** Payment terms agreed between **UpBase** and the vendor.
    *   **Purpose:** Contains master information about vendors supplying to **UpBase**, including contact details, shipping addresses, and critical financial terms.

**Potential Use Cases:**
<br>- Aiding **UpBase** in demand forecasting and inventory optimization across its multiple e--commerce platforms.
<br>- Analyzing vendor performance to strengthen **UpBase's** procurement negotiations.
<br>- Conducting profitability analysis per SKU, brand, or platform to refine **UpBase's** product catalog and channel strategy.
<br>- Identifying SKUs at risk of stockout or overstock, especially for peak seasons.
<br>- Developing data-driven strategies for inventory replenishment and allocation.
<br>- Assessing the impact of different demand scenarios on inventory needs.

**Data Format:**
<br>Microsoft Excel (.xlsx)
