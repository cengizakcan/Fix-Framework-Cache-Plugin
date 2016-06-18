# Fix-Framework-Cache-Plugin
Fix Framework Cache Plugin

# TUTORIAL 

	$this->model("cache");

	$options = array(
		'time'   => 10, 
		'dir'    => '../cache',
		'buffer' => true, 
		'load'   => false,  
		'external'=>array(),
		);
		
	$Start = new cache($options);
