# 2019-nCoV 新型肺炎确诊患者相同行程
## 说明
>本数据来源:[2019-nCoV 新型肺炎确诊患者相同行程查询工具](http://2019ncov.nosugartech.com/)  

## data字段说明

```json
{
  "id": "主键",
  "t_date": "日期",
  "t_start": "开始时间",
  "t_end": "结束时间",
  "t_type": "交通类型(1:飞机/2:火车/3:长途客车或大巴/4:公交车/5:出租车/6:其他)",
  "t_no": "车次/车牌/航班号/场所名称",
  "t_memo": "车次附加描述",
  "t_no_sub": "车厢",
  "t_pos_start": "出发站",
  "t_pos_end": "到达站",
  "source": "线索来源链接",
  "who": "线索来源",
  "verified": 1,
  "created_at": "提交时间",
  "updated_at": "修改时间"
}
```