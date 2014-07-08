# Work Log Sublime Text Package WIP

A simple work log syntax highlighter for Sublime Text

## Syntax

`# 1.1.13` Log date.  
`12:00 item description here` Item start time with description.  
`13:00 b` Item end time. Via a break symbol ends the the current duration.  
`14:00 #TagName: item description here` Tag for client/project, same as above but enables grouping of durations.  


## Example Work Log file:

`work.wl`

	# 6.9.13
	10:00 first task
	11:00 b
	12:30 #ProjectName: another task
	13:30 b

	# 7.9.13
	11:30 update readme, push commits
	11:40 b

## Example Day Schedule:

	M 13.1.14
	T 14.1.14
	W 15.1.14
	T 16.1.14
	F 17.1.14
	S 18.1.14
	S 19.1.14