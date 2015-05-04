# city
全国省市县（区）三级联动插件
# 使用
++++++++++++++++
<select id="province" class="form-control">
  <option selected="selected" value="">省份</option> 
</select>
<select id="city" class="form-control">
  <option selected="selected" value="">城市</option>
</select>
<select id="county" class="form-control">
  <option selected="selected" value="">区域</option> 
</select>
<input type="hidden" id="position" name="position" value="">
<input type="hidden" id="area" name="area" value="">
<input type="text" class="form-control" name="address" id="address" value="">
$(function(){
	$("#dz").city();
});
+++++++++++++++++
