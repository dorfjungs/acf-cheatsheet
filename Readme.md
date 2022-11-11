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
