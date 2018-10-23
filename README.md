public Map<String, Integer> wordLen(String[] strings) {
  
  Map<String, Integer> map = new HashMap<String, Integer>();
  
  for(int i = 0; i < strings.length; i++){
  	if (map.containsKey(strings[i])){
    	continue;
    }
    else {
    	String oneString = strings[i];
    	map.put(strings[i], oneString.length());
    }
  }
  
  	return map;
}
