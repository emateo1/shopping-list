<!doctype html>
<html lang="en">
	<head>
		<meta charset="UTF-8">
		<title>Esmeralda's Shopping List APP</title>
		<link rel="stylesheet" href="stylesheet.css">
	</head>
	<body>
		<div id="page_holder">
			<h1>Shopping List</h1>
			<div id="input_box">
				<input type="button" class="clicker" id="add_button" value="Add Item">
				<input type="text" class="clicker" id="item_input" placeholder="Your item..." autocomplete="off">
				<div id="price_holder">
					Total $: <span id="totalPrice"></span> 
				</div>
			</div>
			<div id="list_holder">
				<ul id="items_list">
					<li class="ui-state-default" id="item1">
						<div class="item_container">
							<input type="checkbox" class="checkbox" value="Item 1">Item 1
							<select class="item_type">
								<option value="undefined">Type...</option>
								<option value="groceries">Groceries</option>
								<option value="supplies">Supplies</option>
								<option value="clothing">Clothing</option>
								<option value="entertainment">Entertainment</option>
							</select>
							<div class="price_input">
								$<input type="text" class="item_price" size="6" placeholder="Price..." autocomplete="off">
							</div>
						</div>
					</li>
					<li class="ui-state-default" id="item2">
						<div class="item_container">
							<input type="checkbox" class="checkbox" value="Item 2">Item 2
							<select class="item_type">
								<option value="undefined">Type...</option>
								<option value="groceries">Groceries</option>
								<option value="supplies">Supplies</option>
								<option value="clothing">Clothing</option>
								<option value="entertainment">Entertainment</option>
							</select>
							<div class="price_input">
								$<input type="text" class="item_price" size="6" placeholder="Price..." autocomplete="off">
							</div>
						</div>
					</li>
				</ul>
			</div>
			<div id="clear_holder">
				<input type="button" class="clicker" id="clear_button" value="Clear Selected Items">
			</div>
		</div>
	</body>
</html>
