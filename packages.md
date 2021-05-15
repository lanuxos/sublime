# SUBLIME TEXT 3 USEFUL PACKAGES
	- SideBarEnhancements [The side bar right click menus]
	- Anaconda 
	- Djaneiro [Django snipplet]
	- requirementstxt [Auto complete package name on requirments.txt file]
	- SublimeLinter
	- GitGutter [Show edited line on Gutter]
	- AdvancedNewFile [New file via path and file name type]
	- Emmet [Code faster with the define reg]
	- Markdown Preview [Preview your markdown file instanly on browser]
	- SublimeGit
	- AutoFileName [Auto complete path and filename]
	- BracketHighlighter
	- ColorPicker [Generate color code via color picker]
	- Gutter Color [Show color of lines which contain color/color code]
	- A File Icon
	- Theme - Spacegray
	- Material Theme
	- Text Pastry [Generate repeat, increase number and more]
	- PackageSync [Sync packages and settings through cloud storage or offline file export]
	- View In Browser
	- GhostText
	- FTPSync
	- Open-Include
	- Pretty JSON
	- Alignment

# Djaneiro [Django snipplet]
	# Abbreviation 	Tag
		- autoescape 	{% autoescape %} {% autoescape %}
		- block 	{% block %} {% endblock %}
		- comment 	{% comment %} {% endcomment %}
		- csrf 	{% csrf_token %}
		- cycle 	{% cycle %}
		- debug 	{% debug %}
		- ext 	{% extends "" %}
		- extends 	{% extends "" %}
		- filter 	{% filter %} {% endfilter %}
		- firstof 	{% firstof %}
		- for 	{% for in %} {% endfor %}
		- fore 	{% for in %} {% empty %} {% endfor %}
		- if 	{% if %} {% endif %}
		- ifchanged 	{% ifchanged %} {% endifchanged %}
		- ife 	{% if %} {% else %} {% endif %}
		- ifelse 	{% if %} {% else %} {% endif %}
		- ifeq 	{% ifequal %} {% endifequal %}
		- ifequal 	{% ifequal %} {% endifequal %}
		- ifnotequal 	{% ifnotequal %} {% endifnotequal %}
		- inc 	{% include %}
		- include 	{% include %}
		- load 	{% load %}
		- now 	{% now "" %}
		- regroup 	{% regroup by as %}
		- spaceless 	{% spaceless %} {% endspaceless %}
		- ssi 	{% ssi %}
		- static 	{% static %}
		- templatetag 	{% templatetag %}
		- url 	{% url %}
		- verbatim 	{% verbatim %} {% endverbatim %}
		- widthratio 	{% widthratio %}
		- with 	{% with as %} {% endwith %}
		- trans 	{% trans %}
		- blocktrans 	{% blocktrans with as %} {% endblocktrans %}
	# Non-official stuff
		- super 	{{ block.super }}
		- extrahead 	{% block extrahead %} {% endblock extrahead %}
		- extrastyle 	{% block extrastyle %} {% endblock extrastyle %}
		- var 	{{ }}
		- tag 	{% %}
		- staticu 	{{ STATIC_URL }}
		- media 	{{ MEDIA_URL }}
	# Snippets for Django model fields
		- mauto 	models.AutoField()
		- mbauto 	models.BigAutoField()
		- mbigint 	models.BigIntegerField()
		- mbool 	models.BooleanField()
		- mchar 	models.CharField()
		- mcoseint 	models.CommaSeparatedIntegerField()
		- mdate 	models.DateField()
		- mdatetime 	models.DateTimeField()
		- mdecimal 	models.DecimalField()
		- mduration 	models.DurationField()
		- memail 	models.EmailField()
		- mfile 	models.FileField()
		- mfilepath 	models.FilePathField()
		- mfloat 	models.FloatField()
		- mgip 	models.GenericIPAddressField()
		- mimg 	models.ImageField()
		- mint 	models.IntegerField()
		- mip 	models.IPAddressField()
		- mnullbool 	models.NullBooleanField()
		- mphone 	models.PhoneNumberField()
		- mposint 	models.PositiveIntegerField()
		- mpossmallint 	models.PositiveSmallIntegerField()
		- mslug 	models.SlugField()
		- msmallint 	models.SmallIntegerFiled()
		- mtext 	models.TextField()
		- mtime 	models.TimeField()
		- murl 	models.URLField()
		- musstate 	models.USStateField()
		- muuid 	models.UUIDField()
		- mxml 	models.XMLField()
		- fk 	models.ForeignKey()
		- m2m 	models.ManyToManyField()
		- o2o 	models.OneToOneField()
		- Snippets for Django form fields
	# Abbreviation 	Code
		- fbool 	forms.BooleanField()
		- fchar 	forms.CharField()
		- fchoice 	forms.ChoiceField()
		- fcombo 	forms.ComboField()
		- fdate 	forms.DateField()
		- fdatetime 	forms.DateTime()
		- fdecimal 	forms.DecimalField()
		- fduration 	forms.DurationField()
		- femail 	forms.EmailField()
		- ffile 	forms.FileField()
		- ffilepath 	forms.FilePathField()
		- ffloat 	forms.FloatField()
		- fgip 	forms.GenericIPAddressField()
		- fimg 	forms.ImageField()
		- fint 	forms.IntegerField()
		- fip 	forms.IPAddressField()
		- fmochoice 	forms.ModelChoiceField()
		- fmomuchoice 	forms.ModelMultipleChoiceField()
		- fmuchoice 	forms.MultipleChoiceField()
		- fmuval 	forms.MultipleValueField()
		- fnullbool 	forms.NullBooleanField()
		- fregex 	forms.RegexField()
		- fslug 	forms.SlugField()
		- fsdatetime 	forms.SplitDateTime()
		- ftime 	forms.TimeField()
		- ftchoice 	forms.TypedChoiceField()
		- ftmuchoice 	forms.TypedMultipleChoiceField()
		- furl 	forms.URLField()
		- fuuid 	forms.UUIDField()
	# Snippets for Django Views
		- view 	Function Based View
		- createview 	Generic Create View
		- updateview 	Generic Update View
		- deleteview 	Generic Delete View
		- detailview 	Generic Detail View
		- listview 	Generic List View
		- templateview 	Generic Template View
		- adminview 	Generic Admin View
		- tabularinline 	Tabular Inline View
		- stackedinline 	Stacked Inline View
		- dispatch 	dispatch method for CBVs
		- get_context_data 	get_context_data method for CBVs
		- Snippets for Django Models
		- Abbreviation 	Code
		- Model 	Simple Model Class
		- Model_full 	Full Model Class(with TODOs)
	# Snippets for Python
		- init 	__init__(self, *args, **kwargs)
		- pdb 	import pdb ; pdb.set_trace()
		- ipdb 	import ipdb ; ipdb.set_trace()
		- npdb 	from nose.tools import set_trace; set_trace()
		- traceback 	import traceback; traceback.print_exc();
		- utfc 	coding: utf-8
		- Completions
		- Abbreviation
		- null
		- blank
		- choices
		- db_column
		- db_index
		- db_tablespace
		- default
		- related_name
		- editable
		- error_message
		- help_message
		- primary_key
		- unique
		- unique_together
		- unique_for_date
		- unique_for_month
		- unique_for_year
		- verbose_name
		- verbose_name_plural
		- validators
		- auto_now_add
		- auto_now
		- required
		- label
		- initial
		- widget
		- localized
		- return
		- RequestContext
		- context_instance
		- render_to_response
		- render
		- redirect
		- get_object_or_404
		- get_list_or_404

# Emmet
``` 
ul#nav>li.item$*4>a{Item $}

<ul id="nav">
    <li class="item1"><a href="">Item 1</a></li>
    <li class="item2"><a href="">Item 2</a></li>
    <li class="item3"><a href="">Item 3</a></li>
    <li class="item4"><a href="">Item 4</a></li>
</ul>
```

# Text Pastry
	- Incremental numbers/sequences (1, 2, 3 or 100, 80, 60)
	- Repeatable number ranges (1, 2, 3, 4, 1, 2, 3, 4 or 2, 1, 2, 1, 2, 1)
	- Generate UUIDS (ba18f7fc-c387-46da-9544-ed32e49ce6f8 or D306E86C-918F-4551-95A9-CB9865A4DD2F)
	- Extendable list of presets (Monday, Tuesday, Wednesday or alpha, beta, gamma)
	- Extendable list of commands
	- Create and modify selections
	- Improved paste (paste the first three lines of the clipboard data to the three selected locations)
	- Generate date and number ranges
	- Convert to upper/lower case
	- Duplicate values for pasting (1, 1, 2, 2, 3, 3, 4, 4) or (a, a, a, b, b, b, c, c, c)
