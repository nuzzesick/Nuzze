<template>
  <div class="home container-fluid">
    <div class="container">
      <div class="hi" id="hi">
        <svg
          class="me"
          viewBox="0 0 436 55"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            d="M0.424716 54H11.1882V32.9702H33.0384V54H43.777V3.09091H33.0384V24.0959H11.1882V3.09091H0.424716V54ZM52.4524 54H63.0419V15.8182H52.4524V54ZM57.772 10.8963C60.929 10.8963 63.5142 8.48509 63.5142 5.52699C63.5142 2.59375 60.929 0.182526 57.772 0.182526C54.6399 0.182526 52.0547 2.59375 52.0547 5.52699C52.0547 8.48509 54.6399 10.8963 57.772 10.8963ZM84.1774 3.09091H73.1156L74.1099 38.7372H83.2079L84.1774 3.09091ZM78.6589 54.6463C81.8407 54.6463 84.6 51.9865 84.6248 48.6804C84.6 45.424 81.8407 42.7642 78.6589 42.7642C75.3777 42.7642 72.6681 45.424 72.693 48.6804C72.6681 51.9865 75.3777 54.6463 78.6589 54.6463ZM121.384 3.09091H110.62V54H121.384V3.09091ZM138.915 3.09091H130.96V8.50994C130.96 12.7109 129.469 15.7685 127.803 18.4034L132.476 21.1626C135.981 18.2294 138.915 13.0092 138.915 8.46023V3.09091ZM146.993 54H157.583V31.081C157.583 26.8551 160.268 24.0462 163.797 24.0462C167.278 24.0462 169.614 26.4325 169.614 30.1861V54H179.881V30.6832C179.881 26.7308 182.143 24.0462 185.996 24.0462C189.376 24.0462 191.912 26.1591 191.912 30.4098V54H202.476V28.3217C202.476 20.044 197.555 15.321 190.445 15.321C184.852 15.321 180.502 18.1797 178.936 22.5547H178.538C177.32 18.13 173.417 15.321 168.172 15.321C163.027 15.321 159.124 18.0554 157.533 22.5547H157.086V15.8182H146.993V54ZM269.823 3.09091H259.109V35.108H258.662L236.687 3.09091H227.241V54H238.005V21.9581H238.377L260.526 54H269.823V3.09091ZM303.002 37.7429C303.027 42.8636 299.522 45.5483 295.719 45.5483C291.716 45.5483 289.131 42.7393 289.106 38.2401V15.8182H278.517V40.1293C278.542 49.0533 283.762 54.4972 291.443 54.4972C297.185 54.4972 301.312 51.5391 303.027 47.0646H303.425V54H313.591V15.8182H303.002V37.7429ZM321.863 54H353.955V45.5483H335.759V45.2749L353.308 22.7038V15.8182H322.509V24.2699H340.556V24.5433L321.863 47.6861V54ZM361.853 54H393.945V45.5483H375.749V45.2749L393.298 22.7038V15.8182H362.499V24.2699H380.546V24.5433L361.853 47.6861V54ZM418.349 54.7457C427.795 54.7457 434.159 50.147 435.65 43.0625L425.856 42.4162C424.787 45.3246 422.053 46.8409 418.523 46.8409C413.228 46.8409 409.873 43.3359 409.873 37.6435V37.6186H435.874V34.7102C435.874 21.7344 428.019 15.321 417.926 15.321C406.691 15.321 399.407 23.3004 399.407 35.0831C399.407 47.1889 406.591 54.7457 418.349 54.7457ZM409.873 31.0561C410.096 26.706 413.402 23.2259 418.1 23.2259C422.699 23.2259 425.881 26.5071 425.906 31.0561H409.873Z"
            fill="url(#paint0_linear-884809)"
          />
          <defs>
            <linearGradient
              id="paint0_linear-884809"
              x1="-4"
              y1="29"
              x2="439"
              y2="29"
              gradientUnits="userSpaceOnUse"
            >
              <stop stop-color="#47CCC4" />
              <stop offset="1" stop-color="#4DD895" />
            </linearGradient>
          </defs>
        </svg>
        <span>A Front-end developer based in BA.</span>
      </div>
      <div class="section-container">
        <h6 class="section">About</h6>
        <span class="about-me"
          >Hello, my name is Matías Nuccetelli but everybody calls me: “Nuzze”.
          I'm a 20 years old Front-End Developer born in La Plata, Buenos Aires.
          When I was 16 and I was at high-school, I started coding in HTML &
          CSS, and I was so very excited about these technologies, so at 17, I
          started programming in JavaScript. Currently, I’m working and
          developing a lot on React JS (specifically Next JS for
          server-side-rendering) and Vue JS using CSS Frameworks like Bootstrap,
          Tailwind CSS and others, to build great and fast SPA’s (like this).
          Also, I'm very passionated about the design of application interfaces
          (UI/UX), so before starting to code and build a project, I also design
          and think the whole interface and user experience in design tools such
          like Figma.</span
        >
        <span class="available">Now, I'm available for a job adventure.</span>
        <a class="btn contact" href="mailto:mati280341@gmail.com">Contact me</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "about",
  metaInfo: {
    title: "About",
    titleTemplate: "%s | Nuzze",
    meta: [
      {
        name: "description",
        content: `Hi! I'm Nuzze, a front-end developer based in BA`
      },
      {
        name: "keywords",
        content: `frontend,development,developer,programming,javascript`
      },
      { name: "author", content: `Nuzze` }
    ]
  },
  mounted() {
    var tooltipTriggerList = [].slice.call(
      document.querySelectorAll('[data-toggle="tooltip"]')
    );
    var tooltipList = tooltipTriggerList.map(function(tooltipTriggerEl) {
      return new bootstrap.Tooltip(tooltipTriggerEl);
    });
  }
};
</script>
