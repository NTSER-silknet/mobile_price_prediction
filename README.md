# mobile_price_prediction

```
import joblib
pipeline = joblib.load('pipeline.pkl')
pipeline.predict(df)
```
df should contain following columns from from **dwh_coe_data.dict_devices** table:
- year
- os_name
- internal_memory_size
- ram_capacity
- camera_resolution
- sec_cam_hor_resolution
- sec_cam_ver_resolution
- dual_camera
