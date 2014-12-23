mytestcode
==========
Delete div
var div = document.getElementById("answers");
div.parentNode.removeChild(div);


                                                $.ajax({                                               
                                                url: 'https://github.com/NeilChainani/mytestcode',
                                                type: 'GET',
                                                async: false,
                                                data: {},
                                                complete: function(data) {
                                                console.log(data.responseText)
                                                }});
