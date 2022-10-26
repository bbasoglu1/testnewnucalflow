<template>
  <NucGridPage v-bind:gap="{'col':0,'row':0}" v-bind:rows="[1]"
    v-bind:schema="{'r0-c0':{'col':0,'row':0,'showIn':['xs','sm','md','lg'],'colSpan':1,'rowSpan':1}}"
    v-bind:columns="[1]" overflow="auto" v-bind:designMode="false" v-bind:minNsLimit="0"
    v-bind:style="{'background':'#FFFFFF','paddingTop':'0px','paddingLeft':'0px','paddingRight':'0px','paddingBottom':'0px'}">
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="f0c5fddf-a4c7-485b-9fb6-03dacfb18266" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'height':'auto','background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r0-c0" area="r0-c0">
      <WAlert v-bind:fade="false" v-bind:pill="false" show="false" size="md" v-bind:isLink="false"
        v-bind:squared="false" hrefLink="" alertLabel="This alert will dismiss after time lapse" background="#17a2b8"
        buttonLabel="Show alert with count-down timer" v-bind:dismissible="false" alertVariant="warning"
        dismissLabel="Close" ncTypography="body1" verticalWidth="60px" buttonsVariant="info"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'buttonLabel','displayName':'ButtonLabel'},{'type':'string','propName':'alertLabel','displayName':'AlertLabel'}]}"
        verticalHeight="60px" horizontalWidth="" progressVariant="warning" v-bind:dismissCountDown="5"
        horizontalHeight="" ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF"
        ncClickBorderColor="#17a2b8" ncFocusBorderColor="#17a2b8" ncHoverBorderColor="#17a2b8"
        ncClickBackgroundColor="#17a2b8" ncFocusBackgroundColor="#17a2b8" ncHoverBackgroundColor="#17a2b8"
        position="absolute" top="40.10998307952622%" left="39.29673913043478%" id="e02170d2-c666-4169-873e-db1a0876cec1"
        v-bind:style="{'color':'#FFFFFF','width':'','height':'','fontSize':'9.008px','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'225.2','lineHeight':'13.511999999999999px','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','borderColor':'#fff3cd','borderStyle':'none','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','textDecoration':'none','borderLeftWidth':'0px','borderRightWidth':'0px','horizontalHeight':'','borderBottomWidth':'0px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px','zIndex':2}"/>
    </NucGridCell>
  </NucGridPage>
</template>
<script>
export default {
  name: 'Screen1',
  data() {
    return {};
  },
  props: {},
  created() {},
  mounted() {},
  computed: {},
  methods: {},
  watch: {},
};
</script>

<style scoped></style>