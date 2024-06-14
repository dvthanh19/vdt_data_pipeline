# [Assignment] BUILDING DATA PIPELINE
<div style="margin-left: 170px;">Viettel Digital Talent 2024</div>



  
**Author**: Thanh Dinh  
**Start date**: 29/05/2024  
**Description**: ...


## Architecture
![Data pipeline Architecture](./img/pipeline_arch.png)

## Getting Started

To deploy the system, ensure that you are in */src*, run:
```
docker-compose -f docker-compose.yml -p demo-pipeline up -d
```



broker01:9093,broker02:9095
vdt2024


**Config putHDFS**
/opt/nifi/nifi-current/hdfs_config/core-site.xml,/opt/nifi/nifi-current/hdfs_config/hdfs-site.xml
/raw_zone/fact/activity

**Config putHDFS**





bash
hdfs dfs -put /hadoop/data/danh_sach_sv_de.csv /raw_zone/fact


check lai vi tri spark output