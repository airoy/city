# city
全国省市县（区）三级联动插件
# 使用
++++++++++++++++
<div class="form-group" id="dz">
	<label class="control-label col-sm-4">地址</label>
	<div class="input-group col-sm-8">
		<span class="input-group-addon"><i class="fa fa-road"></i></span>
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
	</div>
</div>
<script src="__ROOT__/statics/js/city.js"></script>
<script type="text/javascript">
	$(function(){
		$("#dz").city();
	});
</script>
+++++++++++++++++
