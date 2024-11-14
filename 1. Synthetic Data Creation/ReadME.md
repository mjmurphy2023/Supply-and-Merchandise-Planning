# Synthetic Data Creation

This folder contains synthetic data created for a supply and merchandise planning project for a hiking apparel and equipment retail company. The data includes tables with essential information on inventory, sales, production, and other key supply chain metrics, designed to enable comprehensive analysis and data-driven decision-making.

---

**calendar.csv**

- date
- day_of_week
- week_number
- month
- quarter
- year
- is_weekend
- is_holiday
- is_working_day
- is_maintenance_day
- notes

---

**suppliers.csv**

- supplier_id
- supplier_name
- contact_name
- phone_number
- email
- address
- city
- state_province
- postal_code
- country
- lead_time_days
- lead_time_variability
- on_time_delivery_rate
- minimum_order_quantity
- payment_terms
- last_inspection_date
- sustainability_score
- certifications
- preferred_supplier
- supplier_rating
- is_disrupted

---

**customers.csv**

- customer_id
- customer_name
- customer_type
- contact_name
- phone_number
- email
- billing_address
- shipping_address
- city
- state_province
- postal_code
- country
- payment_terms
- credit_limit
- account_manager
- customer_segment
- preferred_customer
- date_created

---

**products.csv**

- product_id
- product_name
- category
- sub_category
- brand
- description
- sku
- upc
- price
- cost_price
- size
- color
- material
- weight
- dimensions
- season
- gender
- launch_date
- discontinue_date
- tax_class
- status

---

**bom.csv**

- product_id
- component_id
- component_name
- quantity_required

---

**warehouses.csv**

- warehouse_id
- warehouse_name
- location
- capacity
- manager_name
- contact_number
- opening_date
- status

---

**stores.csv**

- store_id
- store_name
- region
- store_size
- opening_date
- manager_name
- store_type
- contact_number
- address
- status

---

**manufacturing.csv**

- manufacturing_id
- manufacturing_name
- factory_id
- location
- capacity_units
- production_lead_time
- on_time_in_full_rate
- operating_hours
- shift_count
- machine_count
- machine_downtime_rate
- labor_availability
- last_audit_date
- compliance_certificates
- status

---

**inventory_records.csv**

- inventory_id
- product_id
- location_type
- location_id
- quantity_on_hand
- quantity_reserved
- quantity_available
- reorder_point
- safety_stock_level
- last_restock_date
- next_restock_date
- inventory_turnover_rate
- storage_conditions
- expiration_date

---

**production_schedule.csv**

- production_schedule_id
- manufacturing_id
- product_id
- planned_start_date
- planned_end_date
- actual_start_date
- actual_end_date
- planned_quantity
- actual_quantity
- production_status
- shift
- operator_id
- machine_id
- notes

---

**sales_orders.csv**

- order_id
- customer_id
- order_date
- order_status
- total_order_value
- currency
- payment_status
- shipping_method
- shipping_cost
- delivery_date
- discount_code
- tax_amount
- notes

---

**order_line_items.csv**

- order_line_id
- order_id
- product_id
- quantity_ordered
- unit_price
- line_total

---

**backorders.csv**

- backorder_id
- order_id
- product_id
- backorder_quantity
- order_date
- customer_id
- expected_delivery_date
- status

---

**purchase_orders.csv**

- purchase_order_id
- supplier_id
- order_date
- expected_delivery_date
- total_order_value
- currency
- payment_terms
- order_status
- notes

---

**purchase_order_line_items.csv**

- po_line_id
- purchase_order_id
- component_id
- quantity_ordered
- unit_price
- line_total

---

**material_requirements.csv**

- material_requirement_id
- production_schedule_id
- component_id
- required_quantity
- available_quantity
- shortage_quantity
- order_status
- supplier_id
- expected_delivery_date
- unit_cost
- total_cost
- lead_time_days
- last_updated

---

**forecast.csv**

- forecast_id
- product_id
- location_id
- forecast_date
- forecast_period
- forecast_quantity
- forecast_model
- forecast_accuracy
- confidence_interval
- seasonal_adjustment
- last_actuals_date

