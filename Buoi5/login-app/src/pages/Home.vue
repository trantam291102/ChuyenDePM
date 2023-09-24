<script>
//import GetData from "../utils/api.js";
export default {
  name: "App",
  data() {
    return {
      username: "",
      password: "",
    };
  },
  methods: {
    async login() {
      if (this.username && this.password) {
        console.log(this.username, this.password);
        alert(this.username, this.password);
        return;
      }
      alert("Vui long nhap tai khoan va mat khau");
    },
  },
};
</script>
