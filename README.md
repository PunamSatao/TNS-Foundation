class Car {
	private int price;
	private String model;

	public void start() {
		System.out.println("Car Start");
	}

	public void stop() {
		System.out.println("Car stop");
	}

	public void move() {
		System.out.println("Car move");
	}

	public int getPrice() {
		return price;
	}

	public void setPrice(int price) {
		this.price = price;
	}

	public String getModel() {
		return model;
	}

	public void setModel(String model) {
		this.model = model;
	}

}
