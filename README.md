xygrapher
=========

###Description
This module allows students to enter a X/Y Value and see their value graphed along with the other learners in the cohourt.
This module is designed to work within the edX platform using the LTi module.

###Usage
1. In the course, go to Settings > Advanced Settings
2. For Policy Key "advanced_modules" add "lti" to the array
3. For Policy Key "lti_passports" add "test:test:12345" to the array
1. Create a new LTi block
2. Set launch URL to "https://tools.ceit.uq.edu.au/grapher/xygrapher/"
3. Set lti_id to "test"
4. Set custom_parameters:
	- x_axis_label=X Axis
	- y_axis_label=Y Axis
	- multiple_attempts=False
	- require_grade=True
	- submit_button=Submit
	- min_x_value=0
	- max_x_value=100
	- min_y_value=0
	- max_y_value=100
	- showlines=True 				# Shows lines