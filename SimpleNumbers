package fluffy-parakeet;

import java.util.ArrayList;
import java.util.Collections;

public class SimpleNumbers
{
    public static void main(String[] args)
    {
        ArrayList<Integer> numbers = new ArrayList<>();
        ArrayList<Integer> simNum = new ArrayList<>();

        numbers.add(1);
        numbers.add(2);
        for(int i = 3;true;i++){
            numbers.add(i);
            simNum.add(i);

            ArrayList<Integer> bez1iposl = new ArrayList<>(numbers);
            bez1iposl.remove(bez1iposl.size()-1);
            bez1iposl.remove(0);

            int size = simNum.size();

            for(Integer x : bez1iposl){
                if(i%x==0){
                    simNum.remove(simNum.get(simNum.size()-1));
                    break;
                }
            }

            if(size==simNum.size())
            {
                if (simNum.size() != 0)
                    System.out.println(simNum.get(simNum.size() - 1));
            }

        }

    }
}
