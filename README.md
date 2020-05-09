## vue-circular-progress

基于 Vue 的环形进度条

#### 使用说明

1.安装
`npm install illmatic-circular-progress --save`

2.注册：
`import illmaticCircularProgress from 'illmatic-circular-progress';`
`Vue.use(illmaticCircularProgress);`

3.使用
`<illmatic-circular-progress><illmatic-circular-progress/>`

#### 参数

##### props:

circleOptions:{
&nbsp;&nbsp;&nbsp;&nbsp;width: 60,&nbsp;&nbsp;// 圆宽度
&nbsp;&nbsp;&nbsp;&nbsp;height: 60,&nbsp;&nbsp;// 圆高度
&nbsp;&nbsp;&nbsp;&nbsp;borderWidth: 4,&nbsp;&nbsp;// 进度条宽度
&nbsp;&nbsp;&nbsp;&nbsp;borderColor: "#87CEFA",&nbsp;&nbsp;// 进度条颜色
&nbsp;&nbsp;&nbsp;&nbsp;backGroundColor: "#EDEDED"&nbsp;&nbsp;// 进度条底色
}

direction: "clockwise"&nbsp;&nbsp;//进度条方向（顺时针：clockwise，逆时针：anticlockwise）

duration: 100&nbsp;&nbsp;// 总量（例如：100S 或者 100M 都是 100）

current: 40&nbsp;&nbsp;// 当前进度（例如：40S 或者 40M 都是 40）

playState: "running"&nbsp;&nbsp;//进度条状态（运行：running，暂停：paused）
