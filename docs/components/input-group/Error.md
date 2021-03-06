## error-textbox-headref
#### Error Input Textbox

To display textbox with invalid data, include the <code>error</code> prop with <code>Item</code>.

![Preview ios error-textbox-headref](https://github.com/GeekyAnts/NativeBase-KitchenSink/raw/v2.6.1/screenshots/ios/input-error.png)
![Preview android error-textbox-headref](https://github.com/GeekyAnts/NativeBase-KitchenSink/raw/v2.6.1/screenshots/android/input-error.png)

*Syntax*

{% codetabs name="React Native", type="js" -%}
import React, { Component } from 'react';
import { Container, Header, Content, Item, Input, Icon } from 'native-base';
export default class ErrorInputTextboxExample extends Component {
  render() {
    return (
      <Container>
        <Header />
        <Content>
          <Item error>
            <Input placeholder='Textbox with Error Input'/>
            <Icon name='close-circle' />
          </Item>
        </Content>
      </Container>
    );
  }
}
{%- language name="Vue Native", type="vue" -%}
<template>
  <nb-container>
    <nb-header />
    <nb-content>
      <nb-form>
        <nb-item error>
          <nb-input placeholder='Textbox with Error Input' />
          <nb-icon name="close-circle" />
        </nb-item>
      </nb-form>
    </nb-content>
  </nb-container>
</template>
{%- endcodetabs %}
 <p>
    <div id="" class="mobileDevice" style="background: url(&quot;https://docs.nativebase.io/docs/assets/iosphone.png&quot;) no-repeat; padding: 63px 20px 100px 15px; width: 292px; height: 600px;margin:0 auto;float:none;">
        <img src="https://github.com/GeekyAnts/NativeBase-KitchenSink/raw/v2.6.1/screenshots/ios/input-error.png" alt="" style="display:block !important" />
    </div>
</p>
<br />
