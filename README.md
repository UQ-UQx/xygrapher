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
	- x_axis_label=X Axis			# The X Axis Label
	- y_axis_label=Y Axis			# The Y Axis Label
	- multiple_attempts=False		# Whether the user can re-enter their grades
	- require_grade=True			# Whether the user needs a enter grade before seeing the graph
	- submit_button=Submit			# The label for the submission button
	- min_x_value=0					# The minimum X Value bounds for the graph
	- max_x_value=100				# The maximum X Value bounds for the graph
	- min_y_value=0					# The minimum Y Value bounds for the graph
	- max_y_value=100				# The maximum Y Value bounds for the graph
	- showlines=True 				# Shows red lines to help identify the users point