# Vendor-Management-System
project_name = vendormanagement
app_name = vendormanagement
database = postgresql

DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'vms',
        'USER':'postgres',
        'PASSWORD':'prasanjit',
        'HOST': 'localhost',
        'PORT': '5432', 
    }
}

In admin.py i have list out all fields for better visualization of each records
 
/api/vendors/: List all vendors and create a new one.
/api/vendors/<int:pk>/: Retrieve, update, or delete a vendor by ID.
/api/vendors/<int:pk>/performance/: Retrieve performance metrics for a vendor.
/api/purchase_orders/<int:pk>/acknowledge/: Acknowledge a purchase order for a vendor.
/api/purchase_orders/: List all purchase orders and create a new one.
/api/purchase_orders/<int:pk>/: Retrieve, update, or delete a purchase order by ID.
