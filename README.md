# Cube Tools

整理一些和魔方相关的工具

## API

### 粗饼网

 https://github.com/CubingChina/cubingchina 

1. 获取粗饼赛事列表` https://cubingchina.com/api/v0/competition `
2. 获取赛事详情` https://cubingchina.com/api/v0/competition/{alias} `
3. 获取参赛选手 `https://cubingchina.com/api/v0/competition/{alias}/competitors `
4. 获取赛程` https://cubingchina.com/api/v0/competition/{alias}/schedule `

### WCA数据服务

 https://github.com/lz1998/wca-data-service 

1. 根据关键字搜人` http://wcads.lz1998.xin/wcaPerson/searchPeople?q={keywords}`

2. 查询单次成绩和排名` http://wcads.lz1998.xin/wcaSingle/findBestResultsByPersonId?personId={personId} `

3. 查询平均成绩和排名`http://wcads.lz1998.xin/wcaAverage/findBestResultsByPersonId?personId={personId} `

4. 查询某人某项目所有成绩` http://wcads.lz1998.xin/wcaResult/findResultsByPersonIdAndEventId?personId={personId}&eventId={eventId} `

5. 查询某人所有成绩` http://wcads.lz1998.xin/wcaResult/findResultsByPersonId?personId={personId}`

6. 查询赛事信息` http://wcads.lz1998.xin/wcaCompetition/findCompetitionById?id={competitionId} `

   返回多个结果的有参数pageNum，pageSize(max:1000)

### TNOODLE

 https://github.com/thewca/tnoodle 

1. 生成魔方打乱` http://tnoodle.lz1998.xin/scramble/.txt?={eventId} `

