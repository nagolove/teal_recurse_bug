Ошибка в сборке проекта lua-teal -> sri

tl --version
0.13.2+dev

git log
cfb009880bff80ed5f35eaa4c0f5d5fb8bb21e40

stack traceback:
	/home/nagolove/projects/tl//tl.lua:6098: in local 'cmp'
	/home/nagolove/projects/tl//tl.lua:5832: in upvalue 'arg_check'
	/home/nagolove/projects/tl//tl.lua:6158: in local 'cmp'
	/home/nagolove/projects/tl//tl.lua:5801: in upvalue 'match_record_fields'
	/home/nagolove/projects/tl//tl.lua:5815: in upvalue 'match_fields_to_record'
	/home/nagolove/projects/tl//tl.lua:6144: in local 'cmp'
	/home/nagolove/projects/tl//tl.lua:5832: in upvalue 'arg_check'
	/home/nagolove/projects/tl//tl.lua:6158: in local 'cmp'
	/home/nagolove/projects/tl//tl.lua:5801: in upvalue 'match_record_fields'
	/home/nagolove/projects/tl//tl.lua:5815: in upvalue 'match_fields_to_record'
	...	(skipping 142811 levels)
	/home/nagolove/projects/tl//tl.lua:3116: in local 'fn'
	/home/nagolove/projects/tl//tl.lua:3293: in upvalue 'recurse'
	/home/nagolove/projects/tl//tl.lua:3142: in local 'fn'
	/home/nagolove/projects/tl//tl.lua:3293: in upvalue 'recurse'
	/home/nagolove/projects/tl//tl.lua:3116: in local 'fn'
	/home/nagolove/projects/tl//tl.lua:3293: in function </home/nagolove/projects/tl//tl.lua:3273>
	(...tail calls...)
	/home/nagolove/projects/tl//tl.lua:9045: in function 'tl.type_check'
	/home/nagolove/projects/tl//tl.lua:9425: in function 'tl.process_string'
	(...tail calls...)
	/home/nagolove/projects/tl/tl:710: in field '?'
	/home/nagolove/projects/tl/tl:1332: in main chunk
	[C]: in ?


