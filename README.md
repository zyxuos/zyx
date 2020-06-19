</bean>to
<bean id="now" class="java.util.Date"></bean><bean id="userService" class="com.xp.service.impl.UserServiceImpl">
    <property name="name" value="hhh"></property>
    <property name="age" value="17"></property>
    <property name="date" ref="now"></property>
</bean> 
<bean id="now" class="java.util.Date"></bean>
       [xx728Ax,7628x,89xx,29A8x,432x,2012,0.5,0.5,1.5,5]() @*&(zyx20120606)(@*&6)(@*&6)
       @Override
    public boolean equals(Object obj) {
        if (!(obj instanceof Student))
            throw new ClassCastExcepti;
        Student s = (Student) obj;
        return this.name.equals(s.name) && this.age == s.age;
    }
    public class MapDemo {
    public static void main(String[] args) {
        HashMap<Student, String> hm = new HashMap<Student, String>();
        hm.put(new Student("lisi1", 1), "北京");
        hm.put(new Student("lisi2", 2), "上海");
        hm.put(new Student("lisi3", 3), "天津");
        hm.put(new Student("lisi4", 4), "武汉");
        //第一种取出方式 keySet
        Set<Student> keySet = hm.keySet();
        Iterator<Student> it = keySet.iterator();
        while (it.hasNext()) {
            Student stu = it.next();
            String addr = hm.get(stu);
            System.out.println(stu + "--" + addr);
        }
        public class MapDemo {
    public static void main(String[] args) {
        TreeMap<Student, String> tm = new TreeMap<Student, String>();
        tm.put(new Student("lisi4", 1), "武汉");
        tm.put(new Student("lisi1", 4), "北京");
        tm.put(new Student("lisi3", 2), "天津");
        tm.put(new Student("lisi2", 3), "上海");

        Set<Map.Entry<Student, String>> entrySet = tm.entrySet();
        Iterator<Map.Entry<Student, String>> it = entrySet.iterator();
        while (it.hasNext()) {
            Map.Entry<Student, String> stu = it.next();
            System.out.println(stu.getKey() + "--" + stu.getValue());
        }

    }
}.service.impl.UserServiceImpl">
        <constructor-arg name="name" value="哈哈哈"></constructor-arg>
        <constructor-arg name="age" value="18"></constructor-arg>
        <constructor-arg name="date" ref="now"></constructor-arg>ijk
</bean>to

是发给武汉的信源代码。
