# public
打印模拟商场购物折扣找零信息
public static void main(String[] args){
  System.out.println("***消费单***");
  System.out.println("购买物品\t单价\t个数\t金额");
  System.out.println("T恤\t￥245\t￥490");
  System.out.println("网球鞋\t￥570\t2\t570");
  System.out.println("网球拍\t￥330\t1\t￥300");
  int yi=490;
  int xie=570;
  int pai=300
  int zong=yi+xie+pai;
  System.println("总金额："￥+zong);
  System.println("折扣"+0.8);
  double zhehou=zong*0.8;
  System.out.println("折后总金额:￥"+zhehou);
  int shiji=1500;
  System.out.println("找零:"+zhaoling);
  int jifen=(int)zhehou/10;
  System.out.println("本次购物所购的积分:"+jifen);
}
