<template>
  <div>
    <el-container>
      <el-aside width="200px" class="el-aside"></el-aside>
      <el-container>
        <el-header class="el-header"></el-header>
        <el-main class="el-main">
          <el-table
              :data="tableData">
            <el-table-column
                prop="ID"
                label="编号">
            </el-table-column>

            <el-table-column
                prop="name"
                label="用户名">
            </el-table-column>
            <el-table-column
                prop="sex"
                label="性别">
            </el-table-column>
            <el-table-column
                prop="password"
                label="密码">
            </el-table-column>
            <el-table-column
                prop="phone"
                label="手机号">
            </el-table-column>
          </el-table>
        </el-main>
        <el-footer class="el-footer"></el-footer>
      </el-container>
    </el-container>
  </div>
</template>

<script>
export default {
  data() {
    return {
      tableData: [{
        ID: '00000001',
        name: '王小虎',
        sex:'男',
        password:'123456',
        phone:'1312721442'
      }, {
        ID: '00000002',
        name: '王小虎',
        sex:'男',
        password:'123456',
        phone:'1312721442'
      }, {
        ID: '00000003',
        name: '王小虎',
        sex:'男',
        password:'123456',
        phone:'1312721442'
      }, {
        ID: '00000004',
        name: '王小虎',
        sex:'男',
        password:'123456',
        phone:'1312721442'
      }, {
        ID: '00000005',
        name: '王小虎',
        sex:'男',
        password:'123456',
        phone:'1312721442'
      }, {
        ID: '00000006',
        name: '王小虎',
        sex:'男',
        password:'123456',
        phone:'1312721442'
      }, {
        ID: '00000007',
        name: '王小虎',
        sex:'男',
        password:'123456',
        phone:'1312721442'
      }, {
        ID: '00000008',
        name: '王小虎',
        sex:'男',
        password:'123456',
        phone:'1312721442'
      }]
    }
  }
}
</script>

<style >
.el-table__header th {
  padding: 0;
  height: 42px;
  font-size: 10px;
}
.el-header, .el-footer {
  background-color: #B3C0D1;
  color: #333;
  text-align: center;
  line-height: 60px;
}

.el-aside {
  background-color: #D3DCE6;
  color: #333;
  text-align: center;
  line-height: 200px;
}

.el-main {
  background-color: #E9EEF3;
  color: #333;
  text-align: center;
  line-height: 160px;
}

body > .el-container {
  margin-bottom: 40px;
}

.el-container:nth-child(5) .el-aside,
.el-container:nth-child(6) .el-aside {
  line-height: 260px;
}

.el-container:nth-child(7) .el-aside {
  line-height: 320px;
}
</style>
