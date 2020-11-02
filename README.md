class RoadTax{
	public static void main(String args[]){
	int vechicalPrice=98000;
	String stateKey="KA";
	
	switch (stateKey){
		case "KA":float kaRoadTax=0.18f*vechicalPrice;
			  System.out.println(kaRoadTax);
			  break;
		case "MH":float mhRoadTax=0.45f*vechicalPrice;
			  System.out.println(mhRoadTax);
			  break;
		case "AP":float apRoadTax=0.20f*vechicalPrice;
			  System.out.println(apRoadTax);
			  break;
		case "RJ":float rjRoadTax=0.49f*vechicalPrice;
			  System.out.println(rjRoadTax);
			  break;
		case "UP":float upRoadTax=0.12f*vechicalPrice;
			  System.out.println(upRoadTax);
			  break;
		case "JK":float jkRoadTax=0.05f*vechicalPrice;
			  System.out.println(jkRoadTax);
			  break;
		default:System.out.println("Please choose the ka,mh,ap,rj,up,jk");
			  }
		}
}
