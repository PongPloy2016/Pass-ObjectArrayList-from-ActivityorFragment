Intent intent = new Intent();
    Bundle bundle = new Bundle();
bundle.putSerializable("Obj", item);   // Object 
        bundle.putParcelableArrayList("list", (ArrayList<? extends Parcelable>) list); // list 
        intent.putExtras(bundle);

// 
        Bundle bundle = getIntent().getExtras();
        bundle.getSerializable("Obj");
