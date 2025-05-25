## ecommerce-logistics-dataset-vn
Dataset for analyzing e-commerce logistics and inventory management in Vietnam, covering inventory, SKU masterdata, and vendor information for platforms like Shopee, Lazada, Tiki, TikTok.

# Vietnam E-commerce Logistics & Inventory Management Dataset
**Context:**
<br>This dataset is provided within the context of the booming e-commerce market in Vietnam and globally. With significant annual growth (20-25% in Vietnam), driven by platforms like Shopee and TikTok, e-commerce presents both opportunities and challenges. Key global trends include digital payments, omnichannel sales, and personalized customer experiences, with the Asia-Pacific region leading market growth.

<br>However, the current order fulfillment process, especially for businesses in this sector, faces significant challenges during peak seasons (e.g., Double Day sales, Tet holiday), where sales can increase up to fivefold. These challenges include:
<br>- Inefficiencies due to manual processes and increased error risk.
<br>- Lack of tools for quick, data-driven decision-making and real-time tracking.
<br>- Difficulties in demand forecasting and strategic planning.
<br>- Poor transparency, trackability, and inter-departmental data integration.

<br>This dataset is intended to help businesses analyze their operations, extract actionable insights, evaluate the value of platform data, and develop strategies to optimize logistics, manage inventory, and improve overall efficiency, particularly in preparation for high-demand periods.

**Dataset Structure:**
<br>The dataset consists of an Excel file with three distinct sheets, providing a comprehensive view of e-commerce operations:
1. Inventory Data:
<br>Sku_name: Name of the Stock Keeping Unit.
<br>Sku_code: Unique code for the SKU.
<br>shop_account: The e-commerce shop account identifier.
<br>Tiki, Lazada, Shopee, TikTok: Stock levels or presence on respective platforms.
<br>Tiki demand per month, Lazada demand per month, Shopee demand per month, TikTok demand per <br>month: Estimated monthly demand for the SKU on each platform.
<br>DOITarget (days): Days Of Inventory target.
<br>Vendor: The supplier of the SKU.
<br>Brand: The brand of the SKU.
<br>Purpose: Contains inventory levels, multi-channel demand forecasts, and supplier information for each SKU.

2. SKU Masterdata:
<br>Sku Code: Unique code for the Stock Keeping Unit (links to Inventory Data).
<br>Sku Name: Full name of the SKU.
<br>SKU Short Name: Abbreviated name for the SKU.
<br>Primary Vendor: Main supplier for the SKU.
<br>Brand: Brand of the SKU.
<br>Sale Price: Retail price of the SKU.
<br>Base Cost: Cost price of the SKU.
<br>Purpose: Provides a detailed catalog of all SKUs, including naming conventions, primary vendor, brand, and pricing information.

3. VendorMasterdata:
<br>SHOP_ACCOUNT: The e-commerce shop account identifier (links to Inventory Data).
<br>VENDOR: Vendor identifier (links to Inventory Data).
<br>BRAND: Brand associated with the vendor for that shop account.
<br>Vendor Name: Full name of the vendor.
<br>Shipping Adress: Shipping address of the vendor.
<br>Payment Terms (per week): Payment terms agreed with the vendor.
<br>Purpose: Contains master information about vendors, including contact details, shipping addresses, and payment terms.

<br>**Potential Use Cases:**
<br>- Demand forecasting and inventory optimization across multiple e-commerce platforms.
<br>- Vendor performance analysis.
<br>- Profitability analysis per SKU, brand, or platform.
<br>- Identifying SKUs at risk of stockout or overstock, especially for peak seasons.
<br>- Developing data-driven strategies for inventory replenishment and allocation.
<br>- Assessing the impact of different demand scenarios on inventory needs.

<br>**Data Format:**
<br>Microsoft Excel (.xlsx)
