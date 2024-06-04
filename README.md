<h1>组件库</h1>
<html>

<head>
  <meta charset="utf-8">
  <title></title>
  <link rel="stylesheet"  href="/repository/static/css/style.css" type="text/css"/>
  <style>
    * {
    font-family: 'Verdana', sans-serif;
    margin: 0;
    padding: 0;
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box;
}

html {
    color: #61666c;
    font-weight: 300;
    font-size: 1em;
    line-height: 2em;
}

body {
    margin: 0 auto;
    padding-top: 20px;
    max-width: 1000px;
}

thead {
    font-weight: 200;
    font-size: 1.2em;
}

h1 {
    font-weight: 200;
    text-align: center;
    font-size: 1.4em;
    line-height: 3em;
}

a {
    color: #5f5f5f;
    text-decoration: none;
}
    a:hover {
        color: #000;
    }
    a.clear, a.clear:link, a.clear:visited {
        color: #666;
        padding: 2px 0;
        font-weight: 400;
        font-size: 14px;
        margin: 0 0 0 20px;
        line-height: 14px;
        display: inline-block;
        border-bottom: transparent 1px solid;
        vertical-align: -10px;
        -webkit-transition: all 300ms ease-in;
        -moz-transition: all 300ms ease-in;
        -ms-transition: all 300ms ease-in;
        -o-transition: all 300ms ease-in;
        transition: all 300ms ease-in;
    }

input {
    margin: 0 auto;
    font-size: 100%;
    vertical-align: middle;
    *overflow: visible;
    line-height: normal;
    font-family: 'Open Sans', sans-serif;
    font-size: 12px;
    font-weight: 300;
    line-height: 18px;
    color: #555;
    display: inline-block;
    height: 20px;
    padding: 4px 32px 4px 6px;
    margin-bottom: 9px;
    font-size: 14px;
    line-height: 20px;
    color: #555;
    -webkit-border-radius: 3px;
    -moz-border-radius: 3px;
    border-radius: 3px;
    width: 196px;
    background-color: #fff;
    border: 1px solid #ccc;
    -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,0.075);
    -moz-box-shadow: inset 0 1px 1px rgba(0,0,0,0.075);
    box-shadow: inset 0 1px 1px rgba(0,0,0,0.075);
    -webkit-transition: border linear .2s,box-shadow linear .2s;
    -moz-transition: border linear .2s,box-shadow linear .2s;
    -o-transition: border linear .2s,box-shadow linear .2s;
    transition: border linear .2s,box-shadow linear .2s;
}
    input:focus {
        outline: 0;
        border-color: rgba(0,0,0,0.8);
        -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,0.075),0 0 8px rgba(0,0,0,0.6);
        -moz-box-shadow: inset 0 1px 1px rgba(0,0,0,0.075),0 0 8px rgba(0,0,0,0.6);
        box-shadow: inset 0 1px 1px rgba(0,0,0,0.075),0 0 8px rgba(0,0,0,0.6);
    }
    input::-moz-focus-inner {
        padding: 0;
        border: 0;
    }

#search {
    display: block;
    margin-left: auto;
    margin-right: auto;
    width: 250px;
    margin-top: 20px;
    -webkit-box-sizing: content-box;
    -moz-box-sizing: content-box;
    box-sizing: content-box;
    -webkit-appearance: textfield;
    -webkit-transition: all 300ms ease-in;
    -moz-transition: all 300ms ease-in;
    -ms-transition: all 300ms ease-in;
    -o-transition: all 300ms ease-in;
    transition: all 300ms ease-in;
}

table {
    border-collapse: collapse;
    font-size: 0.9em;
    max-width: 100%;
    margin: 20px auto 0;
}

tr {
    outline: 0;
    border: 0;
}
    tr:hover td {
        background: #f6f6f6;
    }
    tr td:first-of-type {
        padding-left: 10px;
        padding-right: 10px;
    }
    tr.parent a {
        color: #9099A3;
    }

th {

    text-align: left;
    font-size: .75em;
    padding-right: 20px;
}
    th + th {
        width: 25%;
    }
    th + th + th + th {
        width: 5%;
    }

td {
    padding: 5px 0;
    outline: 0;
    border: 0;
    border-bottom: 1px solid #edf1f5;
    vertical-align: middle;
    text-align: left;
    -webkit-transition: background 300ms ease-in;
    -moz-transition: background 300ms ease-in;
    -ms-transition: background 300ms ease-in;
    -o-transition: background 300ms ease-in;
    transition: background 300ms ease-in;
}
    td:last-child,th:last-child {
        text-align: right;
        padding-right: 10px;
    }
    td a {
        display: block;
    }

.parent a:hover {
    color: #2a2a2a;
}

footer {
    font-size:12px;
    text-align:center;
}
    footer a {
        text-decoration: underline;
        color:#990012;
    }


    .info-content {
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .register-url {
      font-weight: bold;
      color: #F66F6A;
      cursor: pointer;
      margin-left: 5px;
    }

    .register-url:hover {
      color: #FF8B87;
    }

.devui-alert {
      font-size: 12px;
      border: 1px solid transparent;
      padding: 10px;
      line-height: 20px;
      width: 1000px;
    }

    .devui-alert.devui-alert-info {
      background-color: #e9edfa;
      border-color: #96adfa;
      color: #252b3a;
    }

    .devui-alert a {
      text-decoration: none;
    }

    .devui-alert .devui-alert-icon {
      margin-right: 10px;
    }
  </style>

<style>
    body,html {background:#fff;font-family:"Bitstream Vera Sans","Lucida Grande","Lucida Sans Unicode",Lucidux,Verdana,Lucida,sans-serif;}tr:nth-child(even) {background:#f4f4f4;}th {padding:0.1em 0.5em;}th {text-align:left;font-weight:bold;background:#eee;border-bottom:1px solid #aaa;}#list {border:1px solid #aaa;width:100%;}a {color:#5f5f5f;}a:hover {color:#000;}
  </style>

</head>

<body>
  <div class="info-content">
    <div class="devui-alert devui-alert-info ">
      <span class="devui-alert-icon">
      </span>
     </div>
  </div>
</body>

</html>
/</h1>
<table id="list"><thead><tr><th style="width:55%"><a href="?C=N&O=A">File Name</a>&nbsp;<a href="?C=N&O=D">&nbsp;&darr;&nbsp;</a></th><th style="width:20%"><a href="?C=S&O=A">File Size</a>&nbsp;<a href="?C=S&O=D">&nbsp;&darr;&nbsp;</a></th><th style="width:25%"><a href="?C=M&O=A">Date</a>&nbsp;<a href="?C=M&O=D">&nbsp;&darr;&nbsp;</a></th></tr></thead>
<tbody><tr><td class="link"><a href="../">上级目录/</a></td><td class="大小">-</td><td class="日期">-</td></tr><tr><td class="link"><a href="0_README.txt" title="0_README.txt"></a></td><td class="大小">2.4 KiB</td><td class="date">2018-Dec-01 21:21</td></tr>
<tr><td class="link"><a href="wdcopy" title="wdcopy">wdcopy</a></td><td class="size">-</td><td class="date">2024-Nov-05 07:55</td></tr>
<tr><td class="link"><a href="img" title="img">img</a></td><td class="size"></td>-<td class="date">2018-Dec-03 23:03</td></tr>
<tr><td class="link"><a href="api" title="api">api</a></td><td class="size"</td>-<td class="date">2018-Nov-26 22:28</td></tr>
<tr><td class="link"><a href="css" title="css">css</a></td><td class="size"></td>-<td class="date">2018-Dec-03 23:03</td></tr>
<tr><td class="link"><a href="js" title="js">js</a></td><td class="size"></td>-<td class="date">2018-Nov-25 01:41</td></tr>
</tbody></table>
