<script>
    /** @type {import('./$types').PageProps} */
    let { data } = $props();
</script>

<main>
    <article>
        <h1>A meter ahead</h1>
        <p>
            The <code>meter</code> element in HTML is similar to the <code>progress</code> element, but it's actually a bit simpler 
            than its progressive counterpart. A meter is purely a "read" element meant to display a specific value or measurement, and 
            it is not intended to be used for things like loading states. 
            Important aspects:
            You need to specify a <code>min=""</code>, a <code>max=""</code>, and a <code>value=""</code>. In principle, that's all you need, 
            but to style it more beautifully, you'll need a bit more. It starts like this:
        </p>
    
        <code>
            meter &#123;
            width: 500px;
            height: 25px;
            -webkit-appearance: none; 
            &#125;
        </code>
        
        <p>
            You assign a width, height, and -webkit-appearance. This ensures that you can style the meter itself however you want.
            If you are using a browser that runs on Chromium, you need 
            ::-webkit to make this work. This ensures that the default background is removed so you can choose your own background color:
        </p>
    
        <code>
            meter::-webkit-meter-bar &#123;
            background: none;
            background-color: hsl(0 0% 85%);
            border-radius: 1rem; &#125;
        </code>
    
        <p>
            But now we also want to style the actual value indicator of the meter. One way to do this is by styling the optimum-value, 
            which we apply here like this:
        </p>
    
        <code>
            meter::-webkit-meter-optimum-value &#123;
            background: rgb(86 49 232);
            border-radius: 1rem; &#125;
        </code>
    
        <p>
            Once you've done this, you get a much "nicer" result. So, this is how you can get started with the <code>meter</code> 
            element! And yes, you can also play around with corner shapes, just like I did.
        </p>
    
        <section>
            <meter 
                id="red" min="0" max="252"  value="200">
            </meter>
            <meter 
                id="blue" min="0" max="252"  value="175">
            </meter>
            <meter 
                id="green" min="0" max="252"  value="45">
            </meter>
        </section>
    </article>
</main>

<style>
    
section {
  display: grid;
}
meter {
  width: 500px;
  height: 25px;
  -webkit-appearance: none; 
}

#blue
{
  &::-webkit-meter-bar {
    background: none;
    background-color: hsl(0, 0%, 85%);
    border-radius: 1rem;
    corner-shape: scoop;
  }
  
  &::-webkit-meter-optimum-value {
    background: rgb(86, 49, 232);
    border-radius: 1rem;
    corner-shape: squircle;
  }
}

#red {
  &::-webkit-meter-bar {
  background: none;
  background-color: hsl(0, 0%, 85%);
  border-radius: 30px;
  corner-shape: scoop;
  }
 &::-webkit-meter-optimum-value {
  background: red;
  border-radius: 1rem;
  corner-shape: squircle;
  }
}

#green {
  &::-webkit-meter-bar {
  background: none;
  background-color: hsl(0, 0%, 85%);
  border-radius: 1rem;
  corner-shape: scoop;
  }
 &::-webkit-meter-optimum-value {
  background: green;
  border-radius: 1rem;
  corner-shape: squircle;
  }
}
</style>