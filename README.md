Striped Tables
-------------- 
This script demonstrates a way of create striped tables

See it in action at address
[yamay.github.com](http://yamay.github.com)

You can get effect of striped tables through using function:

	$.stripedTable(tableId,style,parity,applyToMerged);

Parameters:

	tableId       - id of table,
	style         - style of striped columns,
	parity        - 0-apply to even columns, 1-to odd columns,
	applyToMerged - 0-apply to merged cells, 1-do not apply to merged cells.

Usage example:

	In <head> block include next code

	<script type="text/javascript">
		$(document).ready(function()
			{
				$.stripedTable('table','striped',0,0);
			}
		);
	</script>