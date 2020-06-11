# 数据库建模

## 建模的目的
* 减少数据冗余
* 尽量避免数据维护中出现更新，插入和删除异常
    * 插入异常：如果表中的某个实体随着另一个实体而存在
    * 更新异常：如果表中的某个实体随着另一个实体而存在
    * 删除异常：如果删除表中的某一实体则会导致其他实体的消失
* 节约数据存储空间
* 提高查询效率

## 需求分析：全面了解产品设计的存储需求

* 存储需求、数据处理需求、数据的安全性和完整性

## 逻辑设计：设计数据的逻辑存储结构

* 数据实体之间的逻辑关系，解决数据冗余和数据维护异常