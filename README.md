# tag2
activity
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>html activity</title>
</head>
<style>
    .my-table{
        border: 1px solid black;
        width: 100%;
    }
    .my-table thead td{
        border: 1px solid black;
        text-align: center;
    }
    .my-table thead tr td h1{
        margin: 0 auto;
    }
    .my-table tbody td{
        border: 1px solid black;
    }
</style>
<body>
    <div class="content">
        <table class="my-table">
            <thead>
                <tr>
                    <td style="width: 20%; max-width: 20%;"><h1>Header1</h1></td>
                    <td style="width: 30%; max-width: 30%;"><h1>Header2</h1></td>
                    <td style="width: 50%; max-width: 50%;"><h1>Header3</h1></td>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td><div style="padding: 2px;">
                        This cell contains a list
                        <ul> 
                            <li>Apple</li>
                            <li>Banana</li>
                        </ul>
                    </div></td>
                    <td>
                        <div style="padding: 2px;">
                            This cell contains a table
                            <table style="border: 1px solid black;">
                                <tr>
                                    <td>A</td>
                                    <td>A</td>
                                </tr>
                                <tr>
                                    <td>C</td>
                                    <td>D</td>
                                </tr>
                            </table>
                        </div>
                    </td>
                    <td rowspan="2">
                        <div>
                            <img src="download.jpg" width="100%" height="100%" style="position: relative; min-height: 100%;">
                        </div>
                    </td>
                </tr>
                <tr>
                    <td>
                        <div style="padding: 2px;">
                            This cell contains a list
                            <ol>
                                <li>apples</li>
                                <li>banana</li>
                              </ol>  
                        </div>
                    </td>
                    <td>
                        <div style="padding: 2px;">
                            <i><u>row 1, cell<sup>2</sup></u></i>
                            <a href="https://www.facebook.com/?ref=tn_tnmn">Here a link to facebook.com</a>
                        </div>
                    </td>
                </tr>
            </tbody>
        </table>
    </div>
    <br>
    <br>
    <div>
    </div>
</body>
</html>