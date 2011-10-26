# ti_textarea_ex Module

## Description

�e�L�X�g�G���A�ƃe�L�X�g�t�B�[���h�̋@�\���g������Titanium mobile���W���[��(iOS�p)

## Accessing the ti_textarea_ex Module


	var ti_textarea_ex = require("jp.covered");
	
	var textArea = ti_textarea_ex.createTextArea({
		//options
	});
	
	var textField = ti_textarea_ex.createTextField({
		//options	
	});

�I�v�V�����͒ʏ�̃e�L�X�g�t�B�[���h��e�L�X�g�t�B�[���h�Ɠ����B

## Reference


### ___PROJECTNAMEASIDENTIFIER__.function

����

	clear()
	undo()
	redo()
	paste()

�e�L�X�g�G���A�̂�

	cursorLeft()
	cursorRight()
	insertString(text)


### Events

�ʏ�̃C�x���g�ɒǉ����ăe�L�X�g�G���A�̂�

	keyboardChanged	
		fired when the keyboard type changed
		
		Event properties
			source
			type
			kbHeight	�L�[�{�[�h�̍���
			kbWidth	�L�[�{�[�h�̂悱��
			
## Install

�^�[�~�i���ňȉ��̃R�}���h�����s

	`python build.py && unzip jp.covered-iphone-0.1.zip -d /Library/Application�_ Support/Titanium/`

��������

	`python build.py`
	 
�ō쐬���ꂽjp.covered-iphone-0.1.zip���𓀂���
Support/Titanium/modules/iphone�Ɏ蓮�ŃR�s�[

## Usage

tiapp.xml�̃��W���[���̍��ڂɒǉ�

	<modules>
		<module version="0.1">jp.covered</module>
	</modules>

## License

MIT License

Copyright 2010 Shin Morichika (towerofl) http://tempad.info/ Twitter: @towerofl