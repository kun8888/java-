动态拼接表单：
    $form = $('<form style="display: none;"></form>');
    $form.attr("target", "_blank");
    $form.attr("method", "post");
    $form.attr("action", url);// 接口
    $form.append('<input name="errorDatas" value=' + JSON.stringify(errorDatas) + '></input>');// 数据
    $form.appendTo('body');
    $form.submit();
