# study
微信小程序
<view class="body">
   <view class="sousuo">
      <image mode="widthFix" src="{{imgList[0].url}}"></image>
      <input></input>
      <view class="sousou so">搜索</view>
   </view>
   <view class="zhuti">
      <view class="grid" wx:for="{{imgList}}" wx:key="item">
          <image src="{{item.url}}"></image>
          <view>{{item.text}}</view>
      </view>
   </view>
</view>
for循环 学习
