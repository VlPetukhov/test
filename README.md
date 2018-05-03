# test

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Test</title>
    <style rel="stylesheet" type="text/css">
        table {
            border-collapse: collapse;
            border-spacing: 0;
            empty-cells: hide;
            table-layout: auto;
            border-width: 0;
            /*font-family: monospace;*/
            font-size: 32px;
            line-height: 32px;
        }
        tr.fixes td {
            position: relative!important;
            top: 12px;
            font-style: italic;
            color: #2da145;
        }
        td {
            padding: 0;
            text-align: center;
        }
        span.wrong {
            text-decoration: line-through;
            font-style: italic;
            color: #ffa0a1;
        }
        span.insertion {
            font-style: italic;
            color: #0fa7a4;
        }

        .content {
            line-height: 250%;
            font-size: inherit;
        }
        .container {
            font-size: inherit;
            line-height: 100%;
            display: inline-block;
            position: relative;
            text-align: center;
            word-break: keep-all;
            white-space:nowrap;
        }
        .err {
            line-height: 100%;
            font-size: inherit;
            display: inline-block;
            color: #ae4745;
            text-decoration: line-through;
        }
        .fix {
            line-height: 100%;
            font-size: inherit;
            display: inline-block;
            font-style: italic;
            position: absolute;
            color: #0fa7a4;
            top: -100%;
            left: 0;
            width: 100%;
            text-align: center;
        }
    </style>
</head>
<body>
    <table>
        <tbody>
            <tr class="fixes">
                <td>a</td>
                <td></td>
                <td>&nbsp;</td>
                <td></td>
                <td></td>
                <td>&nbsp;</td>
                <td></td>
                <td>as</td>
                <td></td>
                <td>very-very bad</td>

                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>

                <td></td>
                <td></td>
                <td></td>
                <td>a</td>
                <td></td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <td><span class="wrong">e</span></td>
                <td>n</td>
                <td>&nbsp;</td>
                <td>apple</td>
                <td><span class="wrong">re</span></td>
                <td>&nbsp;</td>
                <td>w</td>
                <td><span class="wrong">ere</span></td>
                <td>&nbsp;</td>
                <td><span class="wrong">tasty</span></td>

                <td>&nbsp;</td>
                <td>an</td>
                <td>&nbsp;</td>
                <td>ap</td>
                <td><span class="insertion">p</span></td>
                <td>le</td>

                <td>&nbsp;</td>
                <td>an</td>
                <td>&nbsp;</td>
                <td><span class="wrong">e</span></td>
                <td>p</td>
                <td><span class="insertion">p</span></td>
                <td>le</td>
            </tr>
        </tbody>
    </table>
    <h1>an apple was bad</h1>


    <span class="content">
    <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>ginal
    <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>ginal
    <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>ginal
    <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>ginal
    <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>ginal
    <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>ginal
    <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>ginal
    <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>ginal
    <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>ginal
    <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>ginal
    <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>ginal
    <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>ginal
    <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>ginal
    <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>ginal
    <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>ginal
    <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>ginal
    <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>ginal
    <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>ginal
    <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>ginal
    <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>ginal
    <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>ginal
    <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>ginal
    <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>ginal
    <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>ginal
    <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>ginal
    <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>ginal
    <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>ginal
    <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>ginal
    <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>ginal
    <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>ginal
    <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>ginal
    <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>ginal
    <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>ginal
    <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>ginal
    <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>ginal
        <span class="container"><span class="err">atofgr</span><span class="fix">ori</span></span>gin<span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
            <span class="container"><span class="err">atofgr</span><span class="fix">ori</span>gin</span><span class="insertion">al</span>
    </span>
</body>
</html>
```
