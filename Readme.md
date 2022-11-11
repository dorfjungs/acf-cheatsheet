- [Group](#group)
- [Repeater](#repeater)
- [Text](#text)
- [Textarea](#textarea)
- [Number](#number)
- [Email](#email)
- [Link](#link)
- [WYSIWYG](#wysiwyg)
- [Select](#select)
- [True / False](#true--false)
- [Image](#image)
- [File](#file)
- [Date Picker](#date-picker)
- [Taxonomy](#taxonomy)
- [Post Object](#post-object)

<br>
<br>

### Group
```php
->addGroup('group_field', [
  'label' => __('Group Field', 'djx'),
  'instructions' => '',
  'conditional_logic' => [],
  'wrapper' => ['width' => '100'],
  'layout' => 'block',
])
```
[Official Documentation](https://www.advancedcustomfields.com/resources/group/)
<br>
<br>

### Repeater
```php
->addRepeater('repeater_field', [
  'label' => __('Repeater Field', 'djx'),
  'instructions' => '',
  'conditional_logic' => [],
  'wrapper' => ['width' => '100'],
  'min' => 0,
  'max' => 0,
  'layout' => 'table',
  'button_label' => __('Add', 'djx'),
])
```
[Official Documentation](https://www.advancedcustomfields.com/resources/repeater/)
<br>
<br>

### Text
```php
->addText('text_field', [
  'label' => __('Text Field', 'djx'),
  'instructions' => '',
  'required' => 0,
  'wrapper' => ['width' => '100'],
  'default_value' => '',
  'placeholder' => '',
  'maxlength' => '',
])
```
[Official Documentation](https://www.advancedcustomfields.com/resources/text/)
<br>
<br>

### Textarea
```php
->addTextarea('textarea_field', [
  'label' => __('Textarea Field', 'djx'),
  'instructions' => '',
  'required' => 0,
  'wrapper' => ['width' => '100'],
  'default_value' => '',
  'placeholder' => '',
  'maxlength' => '',
  'rows' => '',
  'new_lines' => 'br',
])
```
[Official Documentation](https://www.advancedcustomfields.com/resources/textarea/)
<br>
<br>

### Number
```php
->addNumber('number_Field', [
  'label' => __('Number Field', 'djx'),
  'instructions' => '',
  'required' => 0,
  'conditional_logic' => [],
  'wrapper' => ['width' => '100'],
  'default_value' => '',
  'placeholder' => '',
  'min' => '',
  'max' => '',
  'step' => '',
])
```
<br>
<br>

### Email
```php
->addEmail('email_field', [
  'label' => __('Email Field', 'djx'),
  'instructions' => '',
  'required' => 0,
  'conditional_logic' => [],
  'wrapper' => ['width' => '100'],
  'default_value' => '',
  'placeholder' => '',
  'prepend' => '',
  'append' => '',
])
```
<br>
<br>

### Link
```php
->addLink('link_field', [
  'label' => __('Link Field', 'djx'),
  'instructions' => '',
  'required' => 0,
  'conditional_logic' => [],
  'wrapper' => ['width' => '100'],
  'return_format' => 'array',
])
```
[Official Documentation](https://www.advancedcustomfields.com/resources/link/)
<br>
<br>

### WYSIWYG
```php
->addWysiwyg('html_content', [
  'label' => __('WYSIWYG Field', 'djx'),
  'instructions' => '',
  'required' => 0,
  'conditional_logic' => [],
  'wrapper' => ['width' => '100'],
  'default_value' => '',
  'tabs' => 'Visual and Text',
  'toolbar' => 'full',
  'media_upload' => 0,
  'delay' => 1,
])
```
[Official Documentation](https://www.advancedcustomfields.com/resources/wysiwyg)
<br>
<br>

### Select
```php
->addSelect('select_field', [
  'label' => __('Select Field', 'djx'),
  'instructions' => '',
  'required' => 0,
  'conditional_logic' => [],
  'wrapper' => ['width' => '100'],
  'choices' => [
    'key-1' => 'Value 1',
  ],
  'default_value' => ['key-1'],
  'allow_null' => 0,
  'multiple' => 0,
  'ui' => 1,
  'return_format' => 'value',
  'placeholder' => '',
])
```
[Official Documentation](https://www.advancedcustomfields.com/resources/select/)
<br>
<br>

### True / False
```php
->addTrueFalse('truefalse_field', [
  'label' => __('True / False Field', 'djx'),
  'instructions' => '',
  'required' => 0,
  'conditional_logic' => [],
  'wrapper' => ['width' => '100'],
  'default_value' => 0,
  'ui' => 1,
  'ui_on_text' => '',
  'ui_off_text' => '',
])
```
[Official Documentation](https://www.advancedcustomfields.com/resources/true-false/)
<br>
<br>

### Image
```php
->addImage('image_field', [
  'label' => __('Image Field', 'djx'),
  'instructions' => __('Aspect-Ratio', 'djx') . ': WWWxHHH',
  'required' => 0,
  'conditional_logic' => [],
  'wrapper' => ['width' => '100'],
  'return_format' => 'array',
  'preview_size' => 'thumbnail',
  'library' => 'all',
  'min_width' => '',
  'min_height' => '',
  'min_size' => '',
  'max_width' => '',
  'max_height' => '',
  'max_size' => '',
])
```
[Official Documentation](https://www.advancedcustomfields.com/resources/image/)
<br>
<br>

### File
```php
->addFile('file_Field', [
  'label' => __('File Field', 'djx'),
  'instructions' => '',
  'required' => 0,
  'conditional_logic' => [],
  'wrapper' => ['width' => '100'],
  'return_format' => 'array',
  'library' => 'all',
  'min_size' => '',
  'max_size' => '',
  'mime_types' => '',
])
```
[Official Documentation](https://www.advancedcustomfields.com/resources/file/)
<br>
<br>

### Date Picker
```php
->addDatePicker('date_picker_date', [
  'label' => __('Date Picker Field', 'djx'),
  'instructions' => '',
  'required' => 0,
  'conditional_logic' => [],
  'wrapper' => ['width' => '100'],
  'display_format' => 'd/m/Y',
  'return_format' => 'Ymd',
  'first_day' => 1,
])
```
[Official Documentation](https://www.advancedcustomfields.com/resources/date-picker/)
<br>
<br>

### Taxonomy
```php
->addTaxonomy('taxonomy_field', [
  'label' => __('Taxonomy Field', 'djx'),
  'instructions' => '',
  'required' => 0,
  'conditional_logic' => [],
  'wrapper' => ['width' => '100'],
  'taxonomy' => 'category',
  'field_type' => 'select',
  'allow_null' => 1,
  'add_term' => 0,
  'save_terms' => 1,
  'load_terms' => 1,
  'return_format' => 'id',
  'multiple' => 0,
])
```
[Official Documentation](https://www.advancedcustomfields.com/resources/taxonomy/)
<br>
<br>

### Post Object
```php
->addPostObject('post_object_field', [
  'label' => __('Post Object Field', 'djx'),
  'instructions' => '',
  'required' => 0,
  'conditional_logic' => [],
  'wrapper' => ['width' => '100'],
  'post_type' => [],
  'taxonomy' => [],
  'allow_null' => 0,
  'multiple' => 0,
  'return_format' => 'object',
  'ui' => 1,
])
```
[Official Documentation](https://www.advancedcustomfields.com/resources/post-object/)
<br>
<br>
